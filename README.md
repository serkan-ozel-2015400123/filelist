# filelist
Cmpe 230 Python

* Requirements: python2

## Command line options 

* -after, files created after a time
* -before, files created before a time
    * format of time YYYYMMDD or YYYYMMDDTHHMMSS
* -bigger, files bigger than a size, append M to a number for megabytes, G for gigabytes and K for kilobytes
* -match, match files according to a regex 
* -zip, zip found files
* -delete, delete found files
* -stats, show stats
    * Total number of files visited
    * Total size of the files visited in bytes
    * Total number of included files
    * Total size of the files included
    * if duplname is set, Total number of files with unique names
    * if duplcont is set, Total number of files with unique content
    * if duplcont is set, Total size of files with unique content
* -nofilelist, do not list files
* -duplname, Print files with same name. 
* -duplcont, Group files with same content. Groups are seperated by "-------" lines
