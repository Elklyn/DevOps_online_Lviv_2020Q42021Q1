 
Task1.Part1 
1)	Log in to the system as root.   
![1 1](https://user-images.githubusercontent.com/72690863/104854097-a6093400-590d-11eb-85f8-97459729521f.png)
2)	Use the passwd command to change the password. Examine the basic parameters of the command. What system file does it change *?  
It change /etc/passwd
![1 2](https://user-images.githubusercontent.com/72690863/104854098-a73a6100-590d-11eb-98ce-2bd50e8cf8df.png)
3)	Determine the users registered in the system, as well as what commands they execute. What additional information can be gleaned from the command execution?  
![1 3](https://user-images.githubusercontent.com/72690863/104854099-a73a6100-590d-11eb-9b5c-821b963634d1.png)
4)	Change personal information about yourself. 
![1 4 1](https://user-images.githubusercontent.com/72690863/104854100-a7d2f780-590d-11eb-9d41-e8b8c4b85e73.png)
![1 4 2](https://user-images.githubusercontent.com/72690863/104854101-a7d2f780-590d-11eb-8e30-3e6c620fa906.png)
5)	Become familiar with the Linux help system and the man and info commands. Get help on the previously discussed commands, define and describe any two keys for these commands. Give examples. 
 ![1 5 1](https://user-images.githubusercontent.com/72690863/104854102-a86b8e00-590d-11eb-8575-dfb39d15c26c.png)
![1 5 2](https://user-images.githubusercontent.com/72690863/104854103-a86b8e00-590d-11eb-94e5-cc5ddb33f9b7.png)
![1 5 3](https://user-images.githubusercontent.com/72690863/104854105-a9042480-590d-11eb-9486-a1789df73db4.png)
![1 5 4](https://user-images.githubusercontent.com/72690863/104854106-a9042480-590d-11eb-8c64-5db7244f3e01.png)
![1 5 5](https://user-images.githubusercontent.com/72690863/104854107-a9042480-590d-11eb-8843-378fa1c901ff.png)
![1 5 6](https://user-images.githubusercontent.com/72690863/104854108-a99cbb00-590d-11eb-8c8e-dbfc583641eb.png)
6)	Explore the more and less commands using the help system. View the contents of files .bash* using commands.  
![1 6 1](https://user-images.githubusercontent.com/72690863/104854109-a99cbb00-590d-11eb-9693-f03646004ba8.png)
![1 6 2](https://user-images.githubusercontent.com/72690863/104854110-aa355180-590d-11eb-89bc-b5c5d990f0a0.png)
![1 6 3](https://user-images.githubusercontent.com/72690863/104854111-aa355180-590d-11eb-85a2-1cba2f4704b1.png)   
7)	* Describe in plans that you are working on laboratory work 1. Tip: You should read the documentation for the finger command.  
![1 7](https://user-images.githubusercontent.com/72690863/104854113-aacde800-590d-11eb-998e-0a4059db0ef4.png)
8)	* List the contents of the home directory using the ls command, define its files and directories. Hint: Use the help system to familiarize yourself with the ls command. 
 ![1 8](https://user-images.githubusercontent.com/72690863/104854114-aacde800-590d-11eb-96b7-c0b961050bae.png)
 
Task1.Part2 
1)	Examine the tree command. Master the technique of applying a template, for example, display all files that contain a character c, or files that contain a specific sequence of characters. List subdirectories of the root directory up to and including the second nesting level.  
![2 1](https://user-images.githubusercontent.com/72690863/104854115-ab667e80-590d-11eb-906b-b69e9f3c32d7.png)
2)	What command can be used to determine the type of file (for example, text or binary)? Give an example.  
![2 2](https://user-images.githubusercontent.com/72690863/104854116-ab667e80-590d-11eb-9ae3-3b25db2007fa.png)
3)	Master the skills of navigating the file system using relative and absolute paths. How can you go back to your home directory from anywhere in the filesystem? 
![2 3](https://user-images.githubusercontent.com/72690863/104854118-abff1500-590d-11eb-836a-72d7e1ddd645.png) 
4)	Become familiar with the various options for the ls command. Give examples of listing directories using different keys. Explain the information displayed on the terminal using the -l and -a switches. 
![2 4](https://user-images.githubusercontent.com/72690863/104854120-abff1500-590d-11eb-971f-9bdc02f1c5a2.png) 
5)	Perform the following sequence of operations: 
-	create a subdirectory in the home directory; 
-	in this subdirectory create a file containing information about directories located in the root directory (using I/O redirection operations); 
-	view the created file; 
-	copy the created file to your home directory using relative and absolute addressing. 
-	delete the previously created subdirectory with the file requesting removal; - delete the file copied to the home directory. 
![2 5 1](https://user-images.githubusercontent.com/72690863/104854121-ac97ab80-590d-11eb-8692-bd2305b224a2.png)
![2 5 2](https://user-images.githubusercontent.com/72690863/104854122-ac97ab80-590d-11eb-8e02-5f53e175c1c8.png)
![2 5 3](https://user-images.githubusercontent.com/72690863/104854123-ad304200-590d-11eb-9f25-18e9165766b0.png)   
6)	Perform the following sequence of operations: 
-	create a subdirectory test in the home directory; 
-	copy the .bash_history file to this directory while changing its name to labwork2; 
-	create a hard and soft link to the labwork2 file in the test subdirectory; 
-	how to define soft and hard link, what do these concepts; )
-	change the data by opening a symbolic link. What changes will happen and why 
-	rename the hard link file to hard_lnk_labwork2; 
-	rename the soft link file to symb_lnk_labwork2 file; 
-	then delete the labwork2. What changes have occurred and why? 
![2 6](https://user-images.githubusercontent.com/72690863/104854125-ad304200-590d-11eb-93e3-cf388e8ad6fb.png)
7)	Using the locate utility, find all files that contain the squid and traceroute sequence.
![2 7](https://user-images.githubusercontent.com/72690863/104854126-adc8d880-590d-11eb-9b5d-bd78535f9ef6.png)
8)	Determine which partitions are mounted in the system, as well as the types of these partitions.
![2 8 1](https://user-images.githubusercontent.com/72690863/104854127-adc8d880-590d-11eb-8550-890899774b45.png)
![2 8 2](https://user-images.githubusercontent.com/72690863/104854128-ae616f00-590d-11eb-866c-dba3d34d9dcd.png)
9)	Count the number of lines containing a given sequence of characters in a given file. 
![2 9](https://user-images.githubusercontent.com/72690863/104854129-aefa0580-590d-11eb-9fd4-e762b71fb230.png) 
10)	Using the find command, find all files in the /etc directory containing the 
host character sequence. 
 ![2 10](https://user-images.githubusercontent.com/72690863/104854130-aefa0580-590d-11eb-806d-cd05531fb3c8.png)
11)	List all objects in /etc that contain the ss character sequence. How can I duplicate a similar command using a bunch of grep? 
 ![2 11](https://user-images.githubusercontent.com/72690863/104854132-af929c00-590d-11eb-82af-943aac5a8ad9.png)
12)	Organize a screen-by-screen print of the contents of the /etc directory. Hint: You must use stream redirection operations. 
 ![2 12 1](https://user-images.githubusercontent.com/72690863/104854133-af929c00-590d-11eb-8252-2d96b6091cfe.png)
![2 12 2](https://user-images.githubusercontent.com/72690863/104854134-b02b3280-590d-11eb-8349-e569828423ff.png)
13)	What are the types of devices and how to determine the type of device? Give examples. 
 ![2 13](https://user-images.githubusercontent.com/72690863/104854135-b02b3280-590d-11eb-9916-b7a64cbb087c.png)
14)	How to determine the type of file in the system, what types of files are there? 
 ![2 14](https://user-images.githubusercontent.com/72690863/104854136-b0c3c900-590d-11eb-9275-9d6075b26fdc.png)
15)	* List the first 5 directory files that were recently accessed in the /etc directory. 
![2 15](https://user-images.githubusercontent.com/72690863/104854138-b0c3c900-590d-11eb-8982-f4ddf91eeca9.png)

