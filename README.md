#Navigation Terminal quote>
**cd** -> Change directory
- cd ~ Change direcory to home
**ls** -> display what is in current directory
**l** -> display complete file information in the directory
**pwd** -> print working directory, the where the hell am I command
**open** -> command will open a file in default program or directory in finder




#File Manipulation 
**man** -> this will pull up manual for commands 
- 'man [commmand here]' -- will display tons of information about the command- q to exit
**|** -> pipe will execute command on left side first then execute command on right
- '[command here]' | [second command here]' -does not work for every command
**>** -> redirects output to a file 
- 'echo 'text to add' > [File Name]' - output directed into file !!!Will overwrite whats in ther.
- 'echo 'text to add' >> [File Name] '- Output appended into file
**mkdir** -> create new directory from current position
**touch** -> create new file within current directory
**mv** -> move files 
- 'mv [current file name] [new file nam]' -- will rename the file
- 'mv [current file name] ./newdirectory/[new file name]' -- will move the file and rename it: . indicates current directory. The directory MUST exist.
**rm** -> removes files or directories --!!! Scary cannot undo
- 'rm [file name]' -- this removes file from system
- 'rm -r [directory name]' -- removes directory and all subsuquest file
**grep** -> will search through documents for strings
-' cat [file name] | grep 'string to search'' -- will search contents of file and return 
- '-n' -- will display line number of found string
- '-A [number here]' -- will display trailing number of lines specified
- '-B [number here]'-- will display preceding number of lines specified
**cat** -> reads a file(s) and outputs to terminal
- 'cat [file name]' - will display file contents
- 'cat [file name] [file name] ...' - will display file contents of all files selected in order

#Git Commands
