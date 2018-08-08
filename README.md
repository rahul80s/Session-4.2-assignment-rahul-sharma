# Session-4.2-assignment-rahul-sharma
Acagild session 4.2 assignment 

1. x <- c(‘data.science.in.R’, ‘machine.learning.in.R’)

Perform the below string Operation:

• Replace the period character "." within each string with another character i.e. "-" minus sign.

2. x <- c('data.science.in.R','machine.learning.in.R')

Perform the below String Operation:

• Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the object.

Ans 1. ->

Replace the period character "." within each string with another character i.e. "-" minus sign. ->

One of the two ways can be used as mentioned below:

a) gsub(".", "-", x) 

b) gsub(".", "-", c(‘data.science.in.R’, ‘machine.learning.in.R’), fixed=TRUE)


Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the object. ->

paste(paste0("-", gsub("\\\\.", "-", c('data.science.in.R’, ‘machine.learning.in.R’))), collapse=" ")
