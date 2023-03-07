# Cloud-Computing-BashScript

## Script #1

### To add my script to Linux PATH :

1- after create the script file in scripts directory using these commands :

a- cd ~/scripts

b- nano LunixStatus

2- I use this command to make the script executable :
    chmod +x LunixStatus 
    
3- to add my script to Linux PATH I use this command :
  sudo cp LunixStatus /usr/local/bin 
  
4- I put the name of my script (LunixStatus) as a command in terminal and it is execute .


### To run script #1 :

1- Download my script file
2- add the script to linux path 
3- type LunixStatus in terminal as a command 
4- it will show the welcome view with current date, current user, Linux version,
and a list of options.
5- choose an option from 1-5 each option show a certain result .
6- any option you choose it will display the result with a sub list that have options from 1-3.
7- you can type command LunixStatus a h p r , it will show you the result fot the 4 arguments and each argument execute an operation using the same methods that used in list of options from 1-5 .
8- to exit from script executing choose 3 if you are in sub menu after choose option from options between 1-5 , or choose 5 if you are in the main options list .

---------------------------------------------------------------------------------------------------------------------------------------------## Script #2

### to add the script to the cronJob :

1- run this command at the terminal : crontab -e  to open the corntab editor.  2- I add a new line to the corntab file ( 0 0 * * * /home/scripts/websiteScript )



