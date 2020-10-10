<h3>Linux-Basic-Commands</h3>

<h1>Basic Linux Commands you will need while working on Unix/Linux</h1>
<p>Commands we type goes via shell (shell is like a brand). Example - Bourne Shell, Korn Shell, bash - bourne again shell, zsh and many more. Every command you run is a utility given to you. Any file/directory whose name starts with ".", it is a hidden file/directory</p>
<code>User ---> (Shell + Utilities) ---> Kernel</code>
<hr>

<strong>Permission:</strong>
<p>Linux was designed to allow many users to access single system at the same time. Also files need to be protected from each other.</p>
<hr>

<ul>
<li>To list all the directories/files: <code>ls</code></li>
<li>To get the long listing version of files/directories: <code>ls -l</code></li>
<li>To clear the screen: <code>Ctrl + L</code> / <code>clear</code></li>
<li>To know what kind of system you are using: <code>uname</code> / <code>uname -a</code></li>
<li>To know the kernel release version: <code>uname -r</code></li>
<li>To get the manual of particular command: <code>man uname</code></li>
<li>To get to know from how much time your system is ON: <code>uptime</code></li>
<li>To change/navigate the directory: <code>cd</code></li>
<li>To know the present working directory: <code>pwd</code></li>
<li>To go one directory back: <code>cd..</code></li>
<li>To create a directory: <code>mkdir _name_</code></li>
<li>To peform the aliasing of commands(temporary): <code>alias ll="ls -l"</code></li>
<li>To list all the files (including hidden ones): <code>ls -a</code></li>
<li>To get today's date: <code>date</code></li>
<li>To get the calendar: <code>cal</code></li>
<li>To get to know how many users are logged in your system: <code>w</code></li>
<li>To get to know from whose credentials you are logged in: <code>whoami</code></li>
<li>To find the location/path of a program/file: <code>whereis _name_</code></li>
<li>To delete/remove a file: <code>rm _name_</code></li>
<li>To delete a directory: <code>rm -r _name_</code> (-r here refers to delete recursively all the files present inside the directory)</li>
<li>Forceful removal: <code>rm -rf _name_</code> (not advised to use)</li>
<li>To create a new file: <code>touch _name_</code></li>
<li>To know what few commands we run previously: <code>history</code></li>
<li>To store the previous commands in afile: <code>histroy > _nameOfFile_</code></li>
<li>To read/open a text/code based file: <code>cat _nameOfFile_</code></li>
<li>To read the head/top part of a file: <code>head _nameOfFile_</code></li>
<li>To read the tail/bottom part of a file: <code>tail _nameOfFile_</code></li>

</ul>
