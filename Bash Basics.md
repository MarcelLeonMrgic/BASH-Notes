These notes are based of "Learn Linux TV - Bashscripting for Beginners" course. This course helped me a lot in setting up my HOMESERVER™ and I can recommend it with only my best intentions. The reason these notes exist are not only to protocoll my learning path but also for quickly looking up knowledge and I hope that they are also useful for you. My writing style is inspired by Beej's Guide to socket programming so enjoy :-).

## Episode 2
==What is a Bash Script? ==
	A Bash Script is a document containing Bash instructions (Who would have thought :-) ) to automate repeating tasks 
==which command==
	which is a command used to identify the location of executables -wikipedia	
	![[Screenshot 2024-12-27 at 08.49.34.png]]
==How to create and execute a Bash Script!==
	1. Note that you are root or write sudo in front of every instruction
	2. create the bash script via ```nano nameOfBashFile.sh```
	3. the very first line of every bash script should be ```#!/bin/bash``` !!! Your bash script might works without it but only if your shell is using bash as its default interpreter. So not writing it is a bad habit.
	4. tell the script what to do for example ```echo "Hello Beej" ```
	5. ```control o + Enter ↵```  to save the file
	6. ```control x ```to leave the file
		1. now that we created our first bash script we have to give it permission via ```chmod +x nameOfBashFile.sh```
	7. to execute our first Bash file write ./nameOfBashFile.sh 
	It should look something like this:![[Screenshot 2024-12-27 at 09.11.55.png]]
	![[Screenshot 2024-12-27 at 09.25.29.png]]
	



Widges:
	manages own databases 
	
	/fscatchedData
	
	
cached database


Containers maps documents loca

NSkey

COntextStoreD