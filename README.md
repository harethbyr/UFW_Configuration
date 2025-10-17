<h1>Uncomplicated Firewall Configuration</h1>



<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>

- <b>Terminal</b> 
- <b>Firewall configuration untilities (sudo, ufw, status, deny, allow)</b>
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux Distro</b>


<h2>Linux Basic Commands:</h2>

<p align ="center">
 To begin with, the PWD command stands for "Print Working Directory" which outputs the current directory of the user. The "whoami" command prints out what the user is logged in as. <br/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />
 The "ls" command prints out a list of files and directories. "ls -l" outputs more information about the files and directories including owner and permissions and "ls -la outputs hidden files. <br/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />
 Another command that is ulitized in Linux is "cd" which stands for change directory. This commands enables you to move to a different folder where different contents are stored. <br/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />
 The locate command searches the directory, path, and files by name. This is very useful because instead of going through every single directory and listing them out, we can use the locate command. Another useful command we can use is the "whereis" command which can also help us find the location of the tool or file.   <br/>
<img src="" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Now that we covered some basics on navigating through the file system, we can go over creating files and one way we can do that is by using the "cat" command. CAT stands for concatenate in which it is used for displaying the contents of a file. However, we can use this command to not only view contents of a file, but to create files. As you can see in the image below, I have typed "cat > TheFastestSportsSedans" in which the ">" operator signals to create the file. After that it will put the system into interactive mode where you can input what ever you would like into the file and to exit the mode you can press "ctrl D". Looking at that image below, we can see the command "cat >> TheFastestSportsSedans"; the ">>" operator simply allows you to append to the file as you can see, I added "3.) Mercedes GT63S". Lastly, to view the contents of the file, you would just input "cat TheFastestSportsSedans" and it will list them.  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Text Manipulation Techniques:</h2>

<p align="center">
 In this section of the project we will go over some text manipulation techniques which in short allows us to modify text by using different tools. In the image below, I decided to "cat" the password list which contains over 80 thousand contents to work with. <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 A useful command that we can use to help use navigate through our contents is the "nl" command which numbers the contents of the file in order. This can be useful if we wanted to know how many contents there are and allow us to reference any line in the file.  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 The first text manipulation technique we can use on is the "grep" command. This command can make our lives way easier because it simply filters out what we are looking for. In the image below, while using password.lst, I added the "| grep apple" after the initial "cat ..." command to specify that I am looking for passwords that have "apple" in them. This can be very useful if you are looking for something specific since some of these files can contain many contents. <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Sometimes people use regular words and word it into a different form to create a password. For example a regular dictionary word would be soul, but a user could use s0ul as their password by replacing the "o" with a "0". The "sed" command allows us to filter through those common passwords and help us find the passwords that are rephrased or written in a different form. In the image below, I used "sed s/o/0/g ...". The "s" stands for substitute, in which we are substituting the "o" with a "0" to help us find the specific passwords written as dictionary but with different letters or numbers. This can be beneficial for us when navigating through contents, as it allows us to find contents that are worded differently. Lastly the "g" stands for global which substitutes at every match of the line. <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
