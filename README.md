Download Link: https://assignmentchef.com/product/solved-pos-433-week-4-systems-administration-scripting-log
<br>
Systems Administration Scripting Log

<strong>To:</strong>

<strong>From:</strong>

<strong>Date:</strong>

As you complete each of the following steps, keep track of what occurs at each point, including what you type, the output given, and any errors experienced. Submit this information in a log to your instructor for this week’s assignment. Your log can use the sample format provided, or you can create your own.

In the same folder as last week, create a new file titled <em>week4prog1[name].scr</em>

Change the permissions on this new file to add the execute bit for user, group, and owner

Run the following script:#!/bin/bash

<ol>

 <li>count=1</li>

 <li>echo “start of the program”</li>

 <li>while [ $count -le 10 ]</li>

 <li>do</li>

</ol>




<ul>

 <li>echo “Loop #$count”</li>

 <li>sleep 10</li>

 <li>count=$[ count + 1 ]</li>

</ul>




<ol>

 <li>done</li>

</ol>

echo “end of the program

Save the script and then run the script in the background.

Use the jobs command to display a list of the jobs currently running

Find the process id of the script and kill the job.

Check to see if you get the trap message.

Run the script again using the at command to schedule the job in the future. Wait for the job to run to make sure it executes.