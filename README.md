In this assignment, I created a folder named Submissions. I used the command mkdir Submissions to create a directory in my area: saleemuddin1. Through file access permission commands, I allowed TA's and Professors access to read and execute files from, but I restricted write access. I used the command chmod -R g-w Submissions to remove write access to groups. I used the command chmod -R o-rx Submissions to restrict read and exectue access, and it was already restricted write access. This does not allow other students to read, write, and execute access. In order to change the ownership and group to the TAs and Professor, the following commands would be used. To change group, the command is chgrp -R cumoja1@gsuad.gsu.edu umahmood1@gsuad.gsu.edu Submissions. To change ownership, the command is chown -R cumoja1@gsuad.gsu.edu umahmood1@gsuad.gsu.edu Submissions. For the second part of the assignment, I copied The Hunger Games txt file found in the cumoja1 directory and placed the copied version in my Submissions folder, which I previously created. I did this using the command cp/home/cumoja1/The\ Hunger\ Games.txt /home/saleemuddin1/Submissions.  Afterwards, I renamed the file, using the mv command, to My Hunger Games.txt: mv The\ Hunger\ Games.txt My\ Hunger\ Games.txt. Then, I viewed the txt file in vi editor and replaced every occurence of a specific character with my Name, Salwa. I used the following command to perform the replace action: %s/Prim/Salwa/g. In the final step, I created this file which details what tasks I completed for this assignment. 
# SLPAssignment
