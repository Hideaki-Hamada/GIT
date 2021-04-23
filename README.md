# BASICS OF GIT IN COMMAND LINE
The following is a Cheat Sheet about Git basics on Linux comand prompt

## LINUX BASICS

	**ls** list documents and folders in a directory. You can check the following variants:
		*ls -a* It shows us the files and directories within the current directory, including hidden files and directories.
		*ls -t* Sort files by modification date.
		*ls -X* Sort by extension
		*ls -l* It shows all the information: user, group, permissions, size, date and time of creation.
		*ls -R* Returns the contents of all subdirectories recursively.

	**man** man displays information about the command and the various attributes that can be used.
		*syntax:* man [command]

	**cd** change directory. Is used for move around into different directories.
		*syntax:* cd [route that you want to access]
			  cd../ (for go back 1 dir) if you want to go more back, only add more: cd../../
	
	**mkdir** creates a new directory. You can even especify the route of the folder.
		*syntax:* mkdir [name of the new dir]
			mkir [route that you want/name]

	**cat** Cat is used to view the content of a file without editing it. It simply shows us its content without the possibility of changing it.
		*syntax:* cat [name.extension]

	**nano** nano is a text editor that is not included in all UNIX versions. for install it use:
		sudo apt-get install nano
				*syntax:* nano [name.extension]


