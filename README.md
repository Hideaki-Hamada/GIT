# BASICS OF GIT IN COMMAND LINE
The following is a Cheat Sheet about Git basics on Linux comand prompt

## LINUX BASICS

	"ls" list documents and folders in a directory. You can check the following variants:
		*ls -a* It shows us the files and directories within the current directory, including hidden files and directories.
		*ls -t* Sort files by modification date.
		*ls -X* Sort by extension
		*ls -l* It shows all the information: user, group, permissions, size, date and time of creation.
		*ls -R* Returns the contents of all subdirectories recursively.

	"man" man displays information about the command and the various attributes that can be used.
		*syntax:* man [command]

	"cd" change directory. Is used for move around into different directories.
		*syntax:* cd [route that you want to access]
			  cd../ (for go back 1 dir) if you want to go more back, only add more: cd../../
	
	"mkdir" creates a new directory. You can even especify the route of the folder.
		*syntax:* mkdir [name of the new dir]
			mkir [route that you want/name]

	"cat" Cat is used to view the content of a file without editing it. It simply shows us its content without the possibility of changing it.
		*syntax:* cat [name.extension]

	"nano" nano is a text editor that is not included in all UNIX versions. for install it use:
		sudo apt-get install nano
				*syntax:* nano [name.extension]

## GIT in a nutshell

"Git is the most commonly used version control system today and is quickly becoming the standard for version control. Git is a distributed version control system, meaning your local copy of code is a complete version control repository. These fully-functional local repositories make it is easy to work offline or remotely."
(Kayla Ngan, Mcrosoft. 2018)

### How to install Git?

Maybe your UNIX distribution have already git installed. For check it type:
	"git -version" if it show you error, then there's not git in your system.

"sudo apt-get install git"

### How to configure Git?

Before to start creating projects from your command line, you must set up git in your system. Let's check how to do it:
	"git config --global user.name [user name]" 
	"git config --global user.email [e-mail]"

Additionally you can configure your prefered editor as default:
	"git config --global core.editor [editor]"

## Cloning repositories

Mnay times you are going to work in a developing team with existing code. You can clone repositories from platforms like "Github" "Gitlab" "Bit Bucket" and in this way be able
to view and edit all the files of that project. Then when you have done, you can try a pull request in order to ask for include your code in the main branch.

### Another uses of cloning

Other times maybe you want to try tools in your system, get curious scripts, or even xploits (in case of cybersecurity). Fot that you can clone the repository of the developer and use it.

"git clone [url of the project] > For this repository it is: git clone https://github.com/Hideaki-Hamada/GIT

try by your own with the following project:

https://github.com/ranger/ranger (Interactive file viewer CLS)

## Starting a repository from 0

If you want to create a blank repository for start a project you can work from the command line.
In this example we are going to work with Github, but it works with others too.

	1- Go to your Github dashboard and create a new repository.
	2- Now create a new directory for all the files that you are going to do
		mkdir [folder name] 
	3- Go to this directory with cd [name of the directory]
	4- "git init" This will generate a new subdirectory called.git, which will contain the repository's data.
	5- You can start creating your files with your prefered editor
	6- add your files.  "git add [name.extention]" if you want to add all "git add -A" if you want to add by extension "git add *.extension"
	7- Commit your changes. "git commit -m "your commit"" (commit must be between quotation marks)
	8- submit your changes. "git push -u [url of the project] then introduce your credentials.


 


### Check if everything is ok with the command "git status"


## Ignoring files 

