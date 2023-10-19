**ls**
1. ls no input<br>
   -the working directory was /home<br>
   -I got the output Lab1 lecture messages because those file are directly within the home<br>
   -there is no error<br>
   ![Image](Lab1_LS_NI.png)<br>
3. ls with a path directory<br>
   -the working directory was /home/lecture1/messages<br>
   -I got the output of the text files because they were all directly within the messages folder<br>
   -there is no error<br>
   ![Image](Lab1_LS_PD.png)<br>
5. ls with a path to a file<br>
   -the working directory was /home/lecture1/messages/en-us-txt<br>
   -I got the working directory as the output because ls can only display the files and folders in a given path<br>
   -there is no error<br>
   ![Image](Lab1_LS_PF.png)<br>
**cd**<br>
1. cd no input<br>
   -the working directory is /home/lecture1/messages<br>
   -there was a change in the directory.. it went back to the home directory <br>
   -this is not an error since no directory was provided to change the directory<br>
   ![Image](Lab1_CD_NI.png)<br>
3. cd with a path directory<br>
   -the working directory is now /home/lecture1<br>
   -there was a change seen in the left next to user lecture1 was added<br>
   -there is no error<br>
   ![Image](Lab1_CD_PD.png)<br>
5. cd with a path to a file<br>
   -the working directory did not change still /home<br>
   -there was an error stating not a directory<br>
   -cd can only be used to change the folder we are in, so we cannot go into a file<br>
   ![Image](Lab1_CD_PF.png)<br>
**cat**<br>
1. cat no input<br>
   -the working directory is /home<br>
   -there is no output<br>
   -this is not an error, cat prints the contents given. since nothing was given, nothing will be printed<br>
   ![Image](Lab1_CAT_NI.png)<br>
3. cat with a path directory<br>
   -the working directory is /home<br>
   -there is a message stating that a Is a directory<br>
   -since a directory to a folder is stated it is unable to print the contents because a file must be specified<br>
   ![Image](Lab1_CAT_PD.png)<br>
5. cat with a path to file<br>
   -the working directory is /home<br>
   -the output is Hello World!<br>
   -there is no error, the command prints the contents of the file specified<br>
   ![Image](Lab1_CAT_PF.png)
