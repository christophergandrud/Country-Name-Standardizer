# Stata do-file for standardising country names

### Created by Christopher Gandrud

### Updated 11 March 2013

---

## No Longer Maintained

I no longer make updates to this repository. Please feel free to fork the repository and keep maintaining it. 

If you are using R and want to have similar capabilities, I highly recommend using the [countrycode](http://cran.r-project.org/web/packages/countrycode/index.html) package.

---

**Summary**: If you regularly put together data sets for cross-country analysis, you'll probably know that it's a real pain to standardise country names so that you can merge together files from different sources.

For example, you want to merge two data sets: A and B. In data set A the country Bosnia and Herzegovina is referred to as "Bosnia-Hertz" and in B it is called "Bosnia-Herzegovina". To merge them into one file that you can use for data analysis you have to find this discrepancy and then change at least one of the names so that they both are the same. This is really tedious to do across multiple data sets with tens or hundreds of countries.

These two files overcome this problem by standardising country names and adding their IMF country code.

The two files here clearly only standardises country name variations that I've come across. An easy way to check if a country name has not been standardised is to see if the do-file did not attach an IMF country code.

To do this Stata use the code:

list country if imfcode == .

Please note: the do-file assumes that the country variable is called "country". 

Hopefully this will save people some time. 

If you use my do-file please cite this Git. Also, feel free to suggest additions/changes.
