Exercise 1 - Introduction to R 1/3 - Practice
================
2024-04-11

## Preparation

1.  Even if you work with R every day, it is (almost) impossible to
    remember all the functions. R has a very good built-in help system,
    but it is not very easy to understand for beginners. This is
    accessible in the Help section. If you want to search specifically,
    you can enter a term in the Help Viewer search window. If you simply
    want to find out what features are available in an installed
    package, you can search for a package in the Packages area and then
    click on it to see the help pages.
2.  If you want to get quick help on a function in the console, you can
    proceed like this: `help(mean)` - This opens the help page for the
    mean function. Alternatively, you can also enter `?mean`.
3.  One can also search for help on a topic. For example, if you need
    help on rounding numbers up or down, you can type `help("round")`.
    More help on the `help()` function can be found like this:
    `help(help)`.

## Practice Exercises

### Operators and Numerical Functions

Calculate using RStudio:

1.  <span style="color:blue; font-size:1.5rem"> <math> <mrow> <mfrac>
    <mrow><mn>1</mn></mrow> <mrow><mn>3</mn></mrow> </mfrac> <mfrac>
    <mrow> <mn>1</mn> <mo>+</mo> <mn>3</mn> <mo>+</mo> <mn>5</mn>
    <mo>+</mo> <mn>7</mn> <mo>+</mo> <mn>2</mn> </mrow> <mrow>
    <mn>3</mn> <mo>+</mo> <mn>5</mn> <mo>+</mo> <mn>4</mn> </mrow>
    </mfrac> </mrow> </math> </span>

2.  How can you calculate Euler’s number
    <span style="color:blue; font-size:1.5rem; font-weight: bold;">ⅇ</span>?

3.  <span style="color:blue; font-size:1.5rem;">√2</span>

4.  <span style="color:blue; font-size:1.5rem;">∛8</span>

5.  <span style="color:blue; font-size:1.5rem;"><i>log<sub>2</sub></i>
    (8)</span>

### Statistical Functions

1.  Create a sequence from 0 to 100 in steps of 5

2.  Calculate the mean value of the vector \[1, 3, 4, 7, 11, 2\].

3.  Display the span from
    <span style="color:blue; font-size:1.5rem;">x<sub>min</sub></span>
    to<span style="color:blue; font-size:1.5rem;">
    x<sub>max</sub></span> of this vector.

4.  Calculate the sum of this vector.

### Data Frames

One advantage of packages like `tidyverse` is that sample data is often
included, making it particularly clear why the packages are useful. We
use the tibble `starwars` from the `tidyverse` package.

#### Homework Task

0.  Get to know the data set ‘starwars’

1.  Who is the shortest character?

2.  Find all characters from Tatooine.

Other questions you might explore:

3.  How many droids are there?

4.  What is the homeworld of Han Solo?

5.  How many characters are there per species? Sort by ascending count.

6.  Change the height from `cm`to `m`.

7.  Filter out all characters that have missing values (`NA`) for their
    mass. How many are left?
