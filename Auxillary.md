# AUX PROJECT 1: SHELL SCRIPTING

In this project I will be adding 20 new Linux users on to a server, by creating a shell script that reads a csv file that contains the first name of the users to be onboarded. 

First I will need to import onboard.sh script on to my instance.

Run the command scp -i (generated pem key for instance) username@public IP:~/;

<code>scp -i ade.pem onboard.sh ubuntu@18.132.12.87:~/;</code>

![alt text](./Images/vi%20onboard%20sh.JPG)


Create a folder called Shell

Create the project folder called Shell

<code>mkdir Shell</code>

Move into the Shell folder

<code>cd Shell</code>

Create a csv file name names.csv

<code> touch names.csv</code>

Open the names.csv file

<code>vim names.csv</code>

Now insert 20 names into names.csv file

![alt text](image.jpg)

