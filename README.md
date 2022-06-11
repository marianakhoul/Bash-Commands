# Bash Commands
Repository to store some shortcut bash commands

Count the number of columns in a tab separated file
```
head -n 1 ${file_name}  | sed 's/\t/,/g' | sed 's/[^,]//g' | wc -c
```
