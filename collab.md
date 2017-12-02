# Collab


# Analysis

## NYC Flight exploration

```r
library (tidyverse)
library (nycflights13) # install.packages("nycflights13")

flights
```

```
## # A tibble: 336,776 x 19
##     year month   day dep_time sched_dep_time dep_delay arr_time
##    <int> <int> <int>    <int>          <int>     <dbl>    <int>
##  1  2013     1     1      517            515         2      830
##  2  2013     1     1      533            529         4      850
##  3  2013     1     1      542            540         2      923
##  4  2013     1     1      544            545        -1     1004
##  5  2013     1     1      554            600        -6      812
##  6  2013     1     1      554            558        -4      740
##  7  2013     1     1      555            600        -5      913
##  8  2013     1     1      557            600        -3      709
##  9  2013     1     1      557            600        -3      838
## 10  2013     1     1      558            600        -2      753
## # ... with 336,766 more rows, and 12 more variables: sched_arr_time <int>,
## #   arr_delay <dbl>, carrier <chr>, flight <int>, tailnum <chr>,
## #   origin <chr>, dest <chr>, air_time <dbl>, distance <dbl>, hour <dbl>,
## #   minute <dbl>, time_hour <dttm>
```

```r
# What do the data look like on January 1st?

flights %>%
  filter (month == 1, 
          day == 1)
```

```
## # A tibble: 842 x 19
##     year month   day dep_time sched_dep_time dep_delay arr_time
##    <int> <int> <int>    <int>          <int>     <dbl>    <int>
##  1  2013     1     1      517            515         2      830
##  2  2013     1     1      533            529         4      850
##  3  2013     1     1      542            540         2      923
##  4  2013     1     1      544            545        -1     1004
##  5  2013     1     1      554            600        -6      812
##  6  2013     1     1      554            558        -4      740
##  7  2013     1     1      555            600        -5      913
##  8  2013     1     1      557            600        -3      709
##  9  2013     1     1      557            600        -3      838
## 10  2013     1     1      558            600        -2      753
## # ... with 832 more rows, and 12 more variables: sched_arr_time <int>,
## #   arr_delay <dbl>, carrier <chr>, flight <int>, tailnum <chr>,
## #   origin <chr>, dest <chr>, air_time <dbl>, distance <dbl>, hour <dbl>,
## #   minute <dbl>, time_hour <dttm>
```
# Perhaps this picture is too big
![more applesauce??](https://static.boredpanda.com/blog/wp-content/uploads/2015/06/pallas-cat-manul-2__880.jpg)

----

![](https://static.boredpanda.com/blog/wp-content/uploads/2015/06/pallas-cat-manul-12__880.jpg)

# This is a dead lynx
![dead lynx](http://mountaintv.net/wp-content/uploads/2015/03/photo0052.jpg)
----

```r
plot(cars)
```

![](collab_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

# This is another dead lynx, just to drive the point home
![dead lynx again](http://www.trapperman.com/forum/attachments/usergals/2012/02/full-398-75185-2012trapline48.jpg)

#oh my...
![oh my...](https://static.boredpanda.com/blog/wp-content/uploads/2015/06/pallas-cat-manul-14__880.jpg)
#Lynx again
![maybe we need text here](https://media1.tenor.com/images/38ac6a4ef23af8e239152c384fb9b1b2/tenor.gif?itemid=5640872)

