1-What command will set a regular users password to force changing it every 90 days? Choose all that apply.
A. useradd –e 90 userpaul 
B. chage –M 90 userpaul 
C. passwd +x 90 userpaul
D. usermod –f 90 userpaul 
E. passwd –x 90 userpaul

answer: B+E

2-You need to change the owner of a file named /var/opt/runme from mireland, who is a member of the users group, to dnelson, who is a member of the editors group. Assuming you want to change both user and group owners, which command will do this?
A. chown mireland dnelson /var/opt/runme
B. chown -u "dnelson" -g "editors" /var/opt/runme C. chown dnelson /var/opt/runme
D. chown dnelson.editors /var/opt/runme

answer:D

3-Which permission, when applied to a directory in the file system, will allow a user to enter the directory?
A. Read
B. Write
C. Execute
D. Access Control

answer:C

4-A user needs to open a file, edit it, and then save the changes. What permissions does he need to do this? (Choose two.)
A. Read
B. Write
C. Execute
D. Modify

answe : A+B

5-A file named employees.odt has a mode of rw-r- -r- -. If rtracy is the file's owner, what can he do with it?
A. He can open the file and view its contents, but he can't save any changes. 
B. He can open the file, make changes, and save the file.
C. He can change ownership of the file.
D. He can run the file if it's an executable.

answer : B

6-A file named employees.odt has a mode of rw-r- -r- -. If mireland is not the file's owner and is not a member of the group that owns this file, what can she do with it?
A. She can open the file and view its contents, but she can't save any changes.
B. She can open the file, make changes, and save the file.
C. She can change ownership of the file.
D. She can run the file if it's an executable.

answer : A

7-A file named myapp has a mode of 755. If dnelson doesn't own this file and isn't a member of the group that owns the file, what can she do with it?
A. She can change the group that owns the file.
B. She can open the file, make changes, and save the file. 
C. She can change ownership of the file.
D. She can run the file.
 
 answer : D

8-You just created a new script file named myapp.sh. However, when you try to run it from the command prompt, the bash shell generates an error that says -bash: ./myapp.sh: Permission denied. Which command will fix this problem?
A. chmod u+r myapp.sh
B. chmod u+x myapp.sh 
C. chmod u+w myapp.sh 
D. chmod u+T myapp.sh

answer : B
