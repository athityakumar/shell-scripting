SHELL-SCRIPTING
---------------
A repository for sample codes of shell-scripting.

REQUIREMENTS
------------

- [x] Knowledge of vi
- [x] Linux OS
- [x] Interest in coding 
- [ ] Infinite amount of coffee (just kidding)

MAKING THE SCRIPTS WORK
-----------------------
(1) In a terminal , type `git clone git@github.com:athityakumar/shell-scripting.git`
<br> (2) Navigate to the scripts folder with `cd shell-scripting/scripts`
<br> (3) Now , type `chmod 755 file-name`
<br> (4) Then , type `./file-name`
<br> (5) Once the favourable output is achieved on running the above command , type `sudo cp file-name ~/../../bin/` to add it as a command to be accessed from the terminal like `file-name arg1 arg2 arg3`
<br> That's it! Happy shell-scripting!

EDITING THE SCRIPTS
-------------------
To change the scripts , type `vi file-name` in terminal.
<br> To insert into file : Press `Esc` , followed by `i` and Tap `Enter`
<br> To save the file : Press `Esc` , followed by `:` , followed by `w` and Tap `Enter`
<br> To quite the file : Press `Esc` , followed by `:` , followed by `q` and Tap `Enter`

WHAT THESE SCRIPTS DO
---------------------

<table>
<tr> <th> # </th> <th> Script </th> <th> Work done by the script</th> </tr>
<tr> <td> (1) </td> <td> <pre>add-command</pre> </td> <td> Adds the shell-scripts as commands by adding them into the <pre>bin/</pre> folder. Requires sudo authentification. </td> </tr>
<tr> <td> (2) </td> <td> <pre>demo</pre> </td> <td> A hello-world equivalent for shell-scripting. Prints details about the <pre>arguments</pre> used along with the command. </td> </tr>
</table>

CONTRIBUTING
------------
The work flow is the same as that of any other repository. 
<br> (1) Fork / clone the repository.
<br> (2) Create a new branch , say `my-changes` and make your changes in this branch.
<br> (3) Commit your changes and send a Pull request (PR) to this repository.
<br> Active contributors would be rewarded with the tag of "Collabrators"
<br> Bug fixes , Issues , Issue solutions , Optimizations & Enhancements are always welcome.

LICENSE
-------
The MIT License - [Athitya Kumar](http://github.com/athityakumar) - All Rights Reserved.