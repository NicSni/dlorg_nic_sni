# Welcome to my dlorg!
## What is dlorg?
Dlorg is an abbrevation (the shortened form) of the concept name DownLoad Organizer.  
It's a script to do what the name implies: Organizing the files of the Download directory.  

The actual script can be found in the [01_script](/01_script) directory with the filename [dlorg_final](01_script/dlorg_final).  

## About:  
This script bases the sorting on file extension (also known as type or fomrmat) and sorts depending on what broader category that file is.  
The categories in the script are as follows:  
*PDFs  
*Text  
*Images  
*Audio  
*Video  
*Programs  
*Web  
*Others  

This is apparent in the script coding as this is formulated using an array to structure the categorization at the beginning of the script.
After the categorization array the files are sorted in an sorting loop. This Loop goes through the files and looks up the extension format. This is then cross-referenced with the previous array to determine category and if it's not found in the array it's categorized as Others. After that the script creates a category directory (if one already doesn't exsist) and moved the file into the determined directory.

Then we have the Inotifywait functions in 2 parts: first go through files already in the directory, and the second monitors for created and moved files. Both then direct it through the sorting loop.  

## How to use: 
All you really need is the script that can be found at [dlorg_final](01_script/dlorg_final).   
The easiest way to get it is by following the link and downloading the file. In the upper right corner there's a download option as pictured below.  
![thuis is where you find the download icon](https://github.com/NicSni/dlorg_nic_sni/blob/main/00_resources/Transfers/img3.png)
Place the script file in an appropriate place, I would suggest an easy to path place.  
Run it from the terminal by going down the file path and preceeding it with ./  

### Setting it up so it runs automatically every start-up
coming soon






