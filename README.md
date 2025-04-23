# Introduction to Data Science - Week 5 Lab 8

This repository contains my **first GitHub publish**, completed during the **Introduction to Data Science** lab subject.  
It was the **only lab I published** as part of the course, marking an important step in learning version control and working with code in a collaborative environment.

## Lab Overview

**Week 5 - Lab 8** focused on working with sequences and vectors in R. The exercises introduced:
- Creating numeric sequences
- Understanding how R handles sequence bounds
- Using the `seq()` function with increments
- Creating character vectors with mixed types
- Accessing vector elements using both positional and logical indexing

## Code Summary

```r
# Creating a sequence from 5 to 13
v <- 5:13
print(v)

# Creating a sequence from 6.6 to 12.6
v <- 6.6:12.6
print(v)

# Final element not part of sequence is discarded
v <- 3.8:11.4
print(v)

# Sequence from 5 to 9 incrementing by 0.4
print(seq(5, 9, by = 0.4))

# Mixed-type vector: logical and numeric values converted to characters
s <- c('apple', 'red', 5, TRUE)
print(s)

# Accessing vector elements using position
t <- c("Sun", "Mon", "Tue", "Wed", "Thurs", "Fri", "Sat")
u <- t[c(2, 3, 6)]
print(u)

# Accessing vector elements using logical indexing (code to be continued)
