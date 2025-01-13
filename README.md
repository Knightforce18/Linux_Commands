# List of Some Useful Linux Commands

 * ## Some General commands:

1. Check your current working directory/location :
   
   ```bash
   $ pwd
    ```
    ![Screenshot_20250113_161439](https://github.com/user-attachments/assets/cd05e4de-5d26-4197-b957-9e90754bad39)
   
2. To display the name of current logged in user : 
   ```bash
   $ whoami
    ```
   ![Screenshot_20250113_161747](https://github.com/user-attachments/assets/2ef2d36c-dd07-4880-807d-4696761c3ad0)
   
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
 ![Screenshot_20250113_162019](https://github.com/user-attachments/assets/197aaa60-5e74-4f9b-90f3-2990bd8e2adb)


4. To display/list files and directories present in current location :
   ~~~bash
   $ ls
   ~~~
   ![Screenshot_20250113_162540](https://github.com/user-attachments/assets/22b8e02f-9436-4a06-ae66-f378bf3e881f)
   
   Options for **ls** command :
   ~~~bash
   $ ls -lt   #This displays latest modified file on the top and it is long listing format.
   
   $ ls -ltr  #This is opposite for command for lt option and output result will be in reverse order.

   $ ls -lh  #This displays the output in human readble and long listing format.
   ~~~
  <br> output format for **ls **command will be in  following manner :
   ~~~bash
   <File-permission> <No. of hard links> <owner-name> <Group> <Modification-date-and-time> <File-size> <File-Name>
   ~~~
   
6.  space for short listing format :
   

7. To clear current Terminal screen:
   ~~~bash
   $ clear
   ~~~
---
* ## Commands related to Files and Directories:

1.  To display content of the file on terminal
   ~~~bash
       $ cat <file-name>
~~~

**Note**: If the file does not have an extension, do not mention it. If the file has an extension, mention the file name along with the extension.<br>

![Screenshot_20250113_163311](https://github.com/user-attachments/assets/ff7b0148-9a29-40ed-95b5-5f5e7c13faca)

2. To create a new file:
   ~~~bash
      $ touch <new_file_name>
   ~~~
   ![Screenshot_20250113_163956](https://github.com/user-attachments/assets/0d324bdd-f02f-47a2-8ae3-5a80a8acda47)
    
**Note**: File name can have an extension or may not have an extension.

   



   
   
