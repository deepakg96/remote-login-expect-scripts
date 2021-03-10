# What is this?
These expect (of TCL extension) scripts lets you login to servers and run tasks remotely. 

# Prerequisites:
	Must have expect utility installed.

# Limitations:
	Since these are expect scripts which you'll probably couple with shell scripts to run tasks on a remote server. The biggest disadvantage of this approach is you open an ssh connection for every command you want to run on remote server. (One could use object oriented languages like Perl to do the same task. If you were to use Perl, you'd get a connection object the very first time you open an ssh connection, you can use the same object to push as many commands as you want. But to do all of this in Perl, you'd have to install certain openssh libraries built for Perl.)

# TODO: 
	Code the same task in Object oriented languages.


/D
