## INSTRUCTIONS
This CTF consists of 3 levels. The first level is very easy and should be completed on the docker VM itself. Whereas the next 2 levels should be completed via the attack machine (Kali-Linux). Please do not open any other folders apart from level_1 on the docker VM, as this may spoil the fun of the challenge :)

### How to run?
Enter the following command on the docker VM, from the root directory of this folder:
$ docker-compose up -d

It may take several minutes to start, as docker will download the necessary modules for setting everything up.

## Level 1:
Open a folder called level_1 on the docker VM, you may find your first flag there!

## Level 2:
The second flag is inside one of the docker containers, the challenge is to get access to this container via the attack machine.


## Level 3:
The mysql username is one of the most famous usernames & the password is a permutation of the string "ctf590a"


Finally, combine the 3 flags that you got, and it will become the password of the final.zip file. Extract this zip file using the combined password to complete the challenge!
