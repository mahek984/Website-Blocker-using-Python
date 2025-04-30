OVERVIEW:

This project is a website blocker build using python. This script will help its users to filter out the website that they don't want to access. The app once executed will ask users to accept if they want to enable the filtering mode and on accepting the prompt(Y/y or N/n), default content filtering will be enabled till the user wants to disable it. User can any time press cancel on app and the filtering will be automatically removed. If no filtering is required at any given point in time then the execution of script can be avoided.

The project also mantains a list of URLs/Domains in a separate file that the user wants to block by enabling filtering mode. This simple text file can be updated anytime and script will automatically fetch the details from the file and filter the websites provided.



PRE-REQUISITES: 

1.Python 3.x installed on machine

2.The script is currently working on Windows & Mac Operating Systems and all Linux Distributions.

3.File containing list of URLs/Domains must be present in same folder as application.

4.Script is required to be executed in admin mode(see details in How to Use section).


HOW TO USE:

1. Getting started:
   
   In order to start utilizing the app, you just need to clone this repository.
   Once cloned successfully, change directory accordingly.
   

3. Updating the blocklist in urllist.txt
   
   Once the blocklist is ready, you are ready to use the app. Execute the script is admin mode(root user) as it is going to edit your host file which requires special privileges. Dont worry the changes will be temporary and will be reflecting only on execution of script. Once the filtering is disabled the host file will return to its normal state.

   -> python websiteblocker.py
