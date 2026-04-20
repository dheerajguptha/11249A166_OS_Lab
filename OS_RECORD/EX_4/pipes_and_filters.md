e. Combined Use of Pipes and Filters
Examples
cat file.txt | grep "OS"
Searches for lines containing OS.
ps -ef | grep root | awk '{print $2}'
Displays process IDs of root processes.
cat file.txt | sed 's/error/ERROR/g'
Replaces lowercase error with uppercase ERROR.
