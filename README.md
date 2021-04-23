# Downloaded files organizer using python 
##### Operating System : Windows Only
### Modules used
1.Built-in Modules:  
sys,os,time  
2.External Modules:  
download the following modules using pip:  
psutil,watchdog
### How to use
1.After installing above modules,run browser_status.py.In browser_status.py make sure correct download path is given in this script.  
2.Make sure that all the three python scripts reside in same directory
3.Run the script from IDLE  
### Working
Whenever a file is downloaded,while this script is running ,it automatically categorize the file based on the file extension  
For example, if a python script is downloaded which has ".py" extension, it goes into "code" folder automatically. 

The file extensions and categories  are collected from   
https://github.com/dyne/file-extension-list  
