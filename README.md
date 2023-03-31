# 2023-group-09

## Name
DIT639 Cyber-Physical Systems and Systems-of-Systems group 9 project

## Description:
This repository contains Group 9's the source files to a system that contains software features for self-driving vehicles in a data-driven way based on a video feedback for DIT639 course: Cyber Physical Systems and Systems of Systems.
A more detailed description will be added after the project progresses more.

## Getting started

1. To clone this repository, make sure you have an active SSH ke. To check if your SSH key is active, you can use this command: 

` ls ~/.ssh/id_rsa.pub ` or 
 `cat ~/.ssh/id_ed25519.pub `

If you have such file on your pc, then this confirms that you have an active SSH key. 

If you dont have an SSH key then follow these steps:  
Generate an SSH key pair on your local machine by running the following command in your terminal: 

`ssh-keygen -t rsa -b 4096` 
 

Follow the prompts to generate the key pair. Make sure to leave the passphrase blank for now. 

Copy the contents of the public key file to your clipboard by running the following command: 

`cat ~/.ssh/id_rsa.pub | pbcopy `

Log in to your Chalmers GitLab account and go to Settings > SSH Keys. 

Click the "Add SSH key" button. 

Paste the contents of your public key into the "Key" field. 

 
2. To clone the project to the right folder where you want it to be:  

first create a folder: 

`mkdir project `

Navigate to the folder: 

`cd project `

then clone the repository to your local machine using the git clone command: 

`git clone git@git.chalmers.se:/courses/dit638/students/2023-group-09 `

 
3. Navigate to the root folder of the repository using the cd command: 

`cd 2023-group-09 `


4. Install and set-up Docker to be able to run the project. You can follow the instructions for installation at (https://docs.docker.com/get-docker/) and on [Docker Compose](https://docs.docker.com/compose/install/). 

 
5. Once you've downloaded docker and docker compose, navigate to the project repository folder in your terminal and run the following command: 

` docker-compose up `

More steps to be added to run the project after more progression..... 


## Technologies: 
- Linux environment(ubuntu)
- c++
- Docker
- CMake
- docker compose

## Documents
- [Code of conduct](https://git.chalmers.se/courses/dit638/students/2023-group-09/-/blob/main/code-of-conduct.md)


## License
For open source projects, say how it is licensed.


## Add Features
* Creating an issue that describes the feature specifically and assign it to one of the developers in the team.
* Start implementing the solution for the feature by writting code.
* Creating a branch with a descriptive name which specifies the functionality of the feature.
* Creating a merge request for reviewing the code with other developers.
* Merging the code after the approval.

## Bug Fixing 
* Creating an issue with a clear description of the error and assign one of the developers.
* Identifying the steps which lead to the error in the code and fix the issue.
* Create a merge request for reviewing the solution.
* After the code has been reviewed, we can merge.

## Commit Messages
* Keep the message concise and to the point.
* Provide more context in the comment section if necessary.
* Use the imperative mood.
* Follow a consistent format for your commit messages throughout the project.

## Authors and acknowledgment
* Akuen Akoi Deng 
* Kanokwan Haesatith
* Nazli Moghaddam
* Cynthia Tarwireyi
* Marwa Selwaye
