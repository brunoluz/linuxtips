|Command|Description|
|-|-|
|**cd -**|Goes to last location|
|-|-|
|**pushd**|Stores a directory in memory in a directory stack|
|**dirs**|Shows the directory stack created by pushd|
|**popd**|Returns the path at the top of the directory stack and remove it from the stack|
|**mkdir -p**|Creates nested directory structure|
|-|-|
|**locate**|Finds files in system using a local database (need to instal mlocate package)|
|**updatedb**|Updates the database used by locate command|
|-|-|
|**man**|System wide documentation that provides short reference manuals for individual commands|
|**info**|Another documentation system originating in the GNU project|
|**--help**|Bash command for getting help|
|**gnome-help** or **yelp**|Graphical help system for Gnome|
|**khelpcenter**|Graphical help system for KDE|
|-|-|
|**reboot**|Restarts the system|
|**shutdown**|Shuts down the system|
|**gnome-session-quit**|Logs you out (gnome only)|
|-|-|
|**at**|Schedules future process to be executed|
|**atq**|Shows scheduled jobs ustimeing at|
|**crontab**|Schedules background process jobs at specific times and/or days on an on-going basis|
|**sleep**|Suspends execution for a specific time|
|-|-|
|**bg**|Returns a stoped background process to running state|
|**fg**|Brings back the process to the foreground|
|**jobs**|Enumerates background processes in the current terminal session|
|*Ctrl + z*|Suspends a foreground process and leave it on background|
|**pstree**|Shows the process tree|
|-|-|
|**diff**|Compares files and directories|
|**diff3**|Compares three different files|
|**cmp**|Compares binary files|
|**patch**|Applies delta files to update files or configuration files|
|**file**|Determites which file type a file is|
|**dd**|Converts and copy files|
|**rsync**|Syncronizes entire directory trees|
|-|-|
|**gzip**|The most frequently used Linux compression utility
|**bzip2**|Produces files significantly smaller than those produced by gzip
|**xz**|The most space-efficient compression utility used in Linux
|**zip**|Is often required to examine and decompress archives from other operating systems
|**tar**|Groups and ungroup files into a single file|
|**gunzip**|Decompress gz files|
|**bunzip2**|Decompress bz2 files|
|**unxz**|Decompress xz files|
|**unzip**|Decompress zip files|
|**time**|Writes to output the time a command took to run|
|-|-|
|**nano**|Simple text editor for CLI|
|**gedit**|Simple text editor for GNOME environment|
|**kwrite**|Simple text editor for KDE environment|
|**kate**|Simple text editor for KDE environment|
|**vi**|Advanced text editor|
|**vim**|vi improved|
|**gvim**|GNOME vi improved|
|**kvim**|KDE vi improved|
|**vimtutor**|Small tutorial for vim text editor|
|**emacs**|Popular advanced text editor|
|-|-|
|**whoami**|Shows current logged user|
|**who**|Shows current logged users|
|**alias**|Creates an alias|
|**unalias**|Removes an alias|
|**useradd**|Adds an user to the system|
|**userdel**|Removes an user from the system|
|**id**|Gives information about the some user|
|**groupadd**|Adds an group to the system|
|**groupdel**|Removes an group from the system|
|**usermod**|Manages users|
|**sudo**|Executes a command with administrative privileges|
|**su**|Substitutes the current user|
|**set**|Shows environment variables|
|**env**|Shows environment variables|
|**export**|Shows environment variables|
|**history**|Shows your command line history|
|-|-|
|**chown**|Changes user ownership of a file or directory|
|**chgrp**|Changes group ownership of a file or directory|
|**chmod**|Changes permissions on the file, which can be owner, group or others|
|-|-|
|**cat**|Prints files and/or concatenate multiple files together|
|**tac**|Prints lines in reverse order|
|**less**|Reads and outputs a file in a buffered manner|
|**head**|Reads the first few lines of each named file and displays on standard output|
|**tail**|Prints the last few lines of each named file and displays it on standard output|
|-|-|
|**zcat**|View a compressed file|
|**zless**|Reads and outputs a compressed file in a buffered manner|
|**zmore**|Reads and outputs a compressed file in a buffered manner|
|**zgrep**|Search inside a compressed file|
|**zdiff**|compare two compressed files|
|-|-|
|**sed**|Stream editor for filtering and transforming text|
|**awd**|Pattern scanning and processing language|
|**sort**|Sort lines of text files|
|**uniq**|Removes duplicates consecutives lines|
|**paste**|Merge lines of files|
|**join**|Join lines of two files on a common field|
|**split**|Split a file into pieces|
|**grep**|Print lines that match patterns|
|**strings**|Print the sequences of printable characters in files|
|**tr**|Translate (replace) or delete characters|
|**tee**|Copy standard input to each FILE, and also to standard output|
|**wc**|Counts the number of lines, words, and characters in a file or list of files|
|**cut**|Manipulates column-based files and is designed to extract specific columns|
|-|-|
|**host**|Show the IP Address of a host|
|**ip**|Show / manipulate routing, network devices, interfaces and tunnels|
|**ifconfig (obsolete)**|Configure a network interface|
|**route (obsolete)**|Show / manipulate the IP routing table|
|**ping**|Send ICMP ECHO_REQUEST to network hosts|
|**traceroute**|Trace a route to a host|
|**ethtool**|Queries network interfaces and can also set various parameters such as the speed|
|**netstat**|Displays all active connections and routing tables. Useful for monitoring performance and troubleshooting|
|**nmap**|Scans open ports on a network. Important for security analysis|
|**tcpdump**|Dumps network traffic for analysis|
|**iptraf**|Monitors network traffic in text mode|  
|**mtr**|Combines functionality of ping and traceroute and gives a continuously updated display|
|**dig**|Tests DNS workings. A good replacement for host and nslookup|
|-|-|
|**wget**|Download a file from internet|
|**curl**|Transfer data from or to a server|