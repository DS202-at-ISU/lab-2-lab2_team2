
<!-- README.md is generated from README.Rmd. Please edit the README.Rmd file -->

# Lab report \#1

Follow the instructions posted at
<https://ds202-at-isu.github.io/labs.html> for the lab assignment. The
work is meant to be finished during the lab time, but you have time
until Monday evening to polish things.

Include your answers in this document (Rmd file). Make sure that it
knits properly (into the md file). Upload both the Rmd and the md file
to your repository.

All submissions to the github repo will be automatically uploaded for
grading once the due date is passed. Submit a link to your repository on
Canvas (only one submission per team) to signal to the instructors that
you are done with your submission.

1-3 1. inspect the first few lines of the data set: what variables are
there? of what type are the variables? what does each variable mean?
what do we expect their data range to be?

There is the address of the property as well as pricing information and
other housing details. The variables are num, char, date types. The
variables describe information for each property such as style (numbers
for the style), occupancy, sale date/price, and living aspects such as
if it has a fireplace, total acres, type of neighborhood, and if it has
AC. We found that most variables are self explanatory for each
variables. Some that we thought were not self explanatory were Style
with 12 different levels, occupancy with a range of 5 levels, and
neighborhood with 42 levels describing if it was an apt on campus,
residential, etc.

2.  is there a variable of special interest or focus? We determined that
    sale price was a good variable to focus on as well as if the
    property was on campus or not.

3.  start the exploration with the main variable:

what is the range of the variable? draw a histogram for a numeric
variable or a bar chart, if the variable is categorical. what is the
general pattern? is there anything odd? follow-up on oddities: see 4

The range is 0 to 20500000 dollars. After making the histogram for the
bedroom variable, we saw that the most houses had roughly 3 bedrooms. We
found that there were some with 7 or more bedrooms which was somewhat
odd.

Blake

``` r
library(classdata)
```

Dhairya

``` r
#this is a comment
```

Hazer

``` r
#this is a comment
```
