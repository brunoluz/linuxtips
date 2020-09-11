# I/O Redirection
|Name           |Symbolic Name|Value|
|---------------|-------------|-----|
|standard input |stdin        |0    |
|standard output|stdout       |1    |
|standard error |stderr       |2    |
__________

# Redirecting Input/Output
Imagine you have a program called **do_something**

## Change input source to a file called **input-file**
./do_something < input-file

## Redirect standart output to a file called **output-file**
./do_something > output-file\
./do_something 1> output-file

## Redirect standart error to a file called **error-file**
./do_something 2> error-file

## Send output and error to a file called **all-output-file**
./do_something > all-output-file 2>&1\
./do_something >& all-output-file

## Redirect strout and stderr to different files
./do_something > output-file 2> error-file

## To append content to existing files use ">>"
./do_something >> output-file\
./do_something 1>> output-file\
./do_something 2>> error-file\
./do_something >> all-output-file 2>>&1\
./do_something >> output-file 2>> error-file