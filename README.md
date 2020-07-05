# BinarySearch

This program will search string within specific range in (binary)file.

To run:

*start /b "" "BinarySearch.exe" "Arg1" Arg2 "Arg3"*  

where:  

Arg1 - path of "to-search" file  
Arg2 - number of bytes (from end of file) where program will search. (0 if you want to search in full file)  
Arg3 - string that you want to find  

Returns:  

0 - If string is not present in file  
1 - If string is present in file within range  
-1 - If file is not exist/can't open  
-2 - If file is empty  
