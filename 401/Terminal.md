# Practice in the Terminal

## The Command Line

The command line, or terminal, is introduced as a text-based interface in Linux.
Users can enter commands and receive text feedback.
The Bash shell is explained as the most common one.
It mentions useful shortcuts, such as command history navigation, for improved productivity.

## Basic Navigation

pwd is introduced to print the current directory.
ls lists directory contents, customizable with options.
Paths can be absolute (root-based) or relative (current location-based).
cd enables you to move within the system, using paths.
Tab completion simplifies path typing.

## More About Files

Linux treats everything as a file, including directories.
The system ignores file extensions; it looks inside files to identify types.
Linux is case-sensitive for file names and command line options.
Handling spaces in file or directory names can be done using quotes or escape characters.
Hidden files and directories begin with a dot (.), and they can be revealed using ls -a.
The file command reveals file types, and you'll practice listing hidden files.

## Manual Pages

Manual pages provide detailed information about commands, including their descriptions, usage, and available options.
The man command is used to access manual pages, followed by the name of the command you want to look up (e.g., man ls).
You can search for specific terms within manual pages using man -k search term.
Within a manual page, you can perform a text search by typing / followed by the search term.

## File Manipulation

mkdir is used to create directories, and you can use options like -p to create parent directories as needed and -v for verbose output.
To remove directories, you can use rmdir, but it only works for empty directories. For non-empty directories, use rm -r.
The touch command creates empty files, and you can use it to modify file access and modification times.
cp is used to copy files and directories. The -r option allows you to copy directories recursively.
mv is used to move or rename files and directories.
rm is used to remove or delete files, and with the -r option, it can remove directories and their contents.

## Cheat Sheet

[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
