#Date: Oct 2019 
#A unix shell devloped in C with many functiinalites like the internal commands(quit,help,dir,pause,environ,echo,clr,..etc), piping,runiing multiple commands, executing commands from a batch file, and running in the background.
To run the program: simply type in "make" then "./myshell"
To run batch file: "make" then "./myshell batchfilename"
Everthing is working except for small bugs:
1- In piping: It's working but when reaching the end of the file after executing "ls -l|more" the program doesn't return to take in more commands so please rerun the program to continue testing))
2- Batchfile is fully working with either single or muultiple commands in each line (didn't handle commands that have pipe in batch file tho)
