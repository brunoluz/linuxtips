## Wildcards

You can search for a filename containing specific characters using wildcards.

|Wildcard|Result|
|-|-|
|?|Matches any single character|
|*|Matches any string of characters|
|[set]|Matches any character in the set of characters, for example [adf] will match any occurrence of a, d, or f|
|[!set]|Matches any character not in the set of characters|
|[a-c]|Maches any character between a and c|
|[!a-c]|Maches any character not between a and c|

To use find command to find md files:\
**$ find . -name "*.md"** 

Is possible to execute commands for each finded file:\
**$ find . -name "*.md" -exec cat {} ';'**

To ask for permission interactively for each file before execute commands, use "-ok" instead of "-exec"
**$ find . -name "*.md" -ok cat {} ';'**

## Finding Files Based on Time

You can search for files based on its attributes, such as when they were created, last used, etc., or based on their size\
|Parameter|Description|
|-|-|
|**-ctime**|Is when the inode metadata (i.e. file ownership, permissions, etc.) last changed; it is often, but not necessarily, when the file was first created.|
|**-atime**|Search for accessed/last read|
|**-mtime**|Search for modified/last written|

To use those parameters you need to specify a time value. It can be expressed as either a number **(n)** that means exactly that value, **+n**, which means greater than that number, or **-n**.\
There are similar options for times in minutes (as in **-cmin**, **-amin**, and **-mmin**).

## Finding Files Based on Size

Usage:\
**$ find / -size 0**

By default the size here is in 512-byte blocks. You can also specify size based on the table below.

|Character|Description|
|-|-|
|**c**|bytes|
|**k**|kilobytes|
|**M**|megabytes|
|**G**|gigabytes|

File sizes can also be exact numbers (**n**), **+n** or **-n**

To find files greater than 10MB:\
**$ find / -size +10M**

## Finding Files Based on Type
**-type d** for directories\
**-type f** for files