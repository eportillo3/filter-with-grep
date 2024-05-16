<h1>Filter with grep</h1>


<h2>Description</h2>
Obtain information contained in server log and user data files.


<h2>Environments Used </h2>

- <b>Linux</b>
- <b>Bash Shell</b>

<h2>Tutorial walk-through:</h2>

<p align="center">
<h3>Task 1:<h3/>
Search for error messages in a log file<br/>
<br/>
<p>1. Navigate to the /home/analyst/logs directory.</p>
<p>2. Use grep to filter the server_logs.txt file, and return all lines containing the text string error.</p>
<img src="https://i.imgur.com/ISPWGwI.png" height="80%" width="80%"/>
<br />
<br />
<h3>Task 2:<h3/>
Find files containing specific strings<br/>
<br />
<p>1. Navigate to the /home/analyst/reports/users directory.</p>
<p>2. Using the pipe character (|), pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names.</p>
<img src="https://i.imgur.com/4JsvRmE.png" height="80%" width="80%"/>
<br />
<br />
3. List the files that contain the word access in their names. <br/>
<img src="https://i.imgur.com/32NJ2c5.png" height="80%" width="80%"/>
<br />
<br />

<h3>Task 3:<h3/>  
Search more file content <br/>
<br/>
<p>1. Display the files in the /home/analyst/reports/users directory.</p>
<p>2. Search the Q2_deleted_users.txt file for the username jhill.</p>
<p>3. Search the Q4_added_users.txt file to list the users who were added to the Human Resources department.</p>
<img src="https://i.imgur.com/4MDzXtL.png" height="80%" width="80%"/>
<br />
<br />

</p>

<h2>Conclusion</h2>

- <b>search for specific information contained in files</b> 
- <b>find files containing specific strings that were piped into grep</b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
