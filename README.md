# upm
User Package Manager is a package manager designed for users on Linux without root access.
## What you need
- python3
- A linux OS
- ```git``` CLI
> [!NOTE]
> Yes, this guide might work on other Unix based operating systems but i don't test upm on other operating systems. You are free to test it on other unix based operating systems but i don't guarantee it will work sucessfully.
## Getting install files
To get the install files just run:
```
git clone --branch install https://github.com/justlleoon/upm
cd upm
```
## Install
Once you are in the upm directory you just cloned, run:
```
chmod +x install
./install
```
## Using upm
Congrats! You installed upm. you can install stuff by using ```upm install {app}``` and remove stuff by going to your ~/.local/bin/ folder and running ```rm {appname}```. 
> [!NOTE]
> ```upm``` only installs apps to your home directory. If you have multiple users, then you will need to install ```upm``` for each of those users.

> [!CAUTION]
> ONLY remove apps that you are sure was installed via ```upm```.
## Finding apps
If you want to look for apps to install using ```upm```, then head over to the GitHub Pages site over [here](https://justlleoon.github.io/upm/).
