# List of Some Useful Linux Commands

 * ## Some General commands:

1. Check your current working directory/location :
   
   ```bash
   $ pwd
    ```
   
2. To display the name of current logged in user : 
   ```bash
   $ whoami
    ```
   
3. To check System date and time :
   ```bash
    $ date
    ```
   
  we can customize the result of the **date** command ,Some examples are following : 
   ```bash

    $ date +%D   # used only for getting the date

    $ date +%T   # used only for getting the current time

    $ date +%H:%M   # used only for getting the current time in HH:MM format

    $ date +%h   # used only for getting the first 3 letters of month name
 ```

4. To display/list files and directories present in current location :
   ~~~bash
   $ ls
   ~~~
   
   Options for **ls** command :
   ~~~bash
   $ ls -lt   #This displays latest modified file on the top and it is long listing format.
   
   $ ls -ltr  #This is opposite for command for lt option and output result will be in reverse order.

   $ ls -lh  #This displays the output in human readble and long listing format.
   ~~~
   output format for **ls **command will be in  following manner :
   ~~~bash
   <File-permission> <No. of hard links> <owner-name> <Group> <Modification-date-and-time> <File-size> <File-Name>
   ~~~
   
5.  space for short listing format :
   

6. To clear current Terminal screen:
   ~~~bash
   $ clear
   ~~~
---
* ## Commands related to Files and Directories:

1.  To display content of the file on terminal
   ~~~bash
       $ cat <file-name>
~~~

**Note**: If the file does not have an extension, do not mention it. If the file has an extension, mention the file name along with the extension.

2. To create a new file:
   ~~~bash
      $ touch <new_file_name>
   ~~~
   
**Note**: File name can have an extension or may not have an extension.

   



   
   
