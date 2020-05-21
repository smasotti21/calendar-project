Diary of a Data Science Student
===============================

How to Avoid Cabin Fever in the age of COVID-19
-----------------------------------------------

### How do I intend to spend my time? How do I actually spend my time?

Motivation + primary questions of interest

COVID-19

I can include an image (not created in R) like this:

![cute puppy](~/git/calendar-project/cute_puppy.png)

Create a “img” folder within your calendar-project repo and store the
image files there.

Data collection
===============

I collected data by . . .

1.  Creating two separate google calendars, one titled “Intended
    Schedule”, and one titled “Actual Schedule”.
2.  Logging the activity for my “intended schedule” for each day every
    morning when I woke up.
3.  Logging the activity for my “actual schedule” every time I finshed
    completing an activity.

I wrangled the data by . . .

1.  Importing the calendars as data frames from google calendar into
    RStudio
2.  Creating variables for length of time spent on activities, category
    of activity, etc.
3.  Assigning specific activities to broader categories for
    classification.

Results
=======

And here are my results . . .

Initial round of visualizations
-------------------------------

### How much time did I intend to spend each day on each activity?

### How much time did I actually spend each day on each activity?

    ## ── Attaching packages ─────────────────────────────────────────────────────────────────────────────────────── tidyverse 1.3.0 ──

    ## ✓ ggplot2 3.2.1     ✓ purrr   0.3.3
    ## ✓ tibble  2.1.3     ✓ dplyr   0.8.4
    ## ✓ tidyr   1.0.2     ✓ stringr 1.4.0
    ## ✓ readr   1.3.1     ✓ forcats 0.4.0

    ## ── Conflicts ────────────────────────────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

    ## 
    ## Attaching package: 'lubridate'

    ## The following object is masked from 'package:base':
    ## 
    ##     date

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-1.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-2.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-3.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-4.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-5.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-6.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-7.png)

    ## Don't know how to automatically pick scale for object of type difftime. Defaulting to continuous.

![](index_files/figure-markdown_strict/unnamed-chunk-2-8.png)
