# Postman-QAChallenge
*
* Steps to run collection in 2 ways  :
*
*S1. Download and intall postman through the below link:
*    https://www.postman.com/downloads/
*S2. Install the postman after downloading is copmpleted
*
*--> Hint: Sign in to postman to never loose you progress
*
*********************************** [ 1st way]**************  run from Command prompt**************************
*Step A. Open CMD (Command runner )
*Step B. Download and install Node js version which is compatible with your machine:
*        https://nodejs.org/en/download/current/
*Step C. Follow the bellow commands to run th e targeted collection from CMD:
*        By installing Node js in step B  >> Newman is just a command away. Install Newman from npm globally on your system, which allows you to run it from anywhere.
*        
*       Run the following : 
*       npm install -g newman    .....(Press enter )  
*        
*        
*       The easiest way to run Newman is to run it with a collection. You can run any collection file from your file system.
*       To  run  the collection :
*       newman run https://www.getpostman.com/collections/df353dd6162705203daa   -n 3             .....(Press enter )  
*       
*       Hint: -n 3 will run the collection for 3 iterations , you can change it bu just change the number after -n 
*        
*        
*********************************** [ 2nd way]**************  run from Postman **************************
*    
*Step A. In postman Press file option 
*Step B. Press Ctrl +O or press import...
*Step C: In the pop-up >> Press link tab 
*Step D: Paste the following collection link:
*        https://www.getpostman.com/collections/df353dd6162705203daa
*Step E. Press continue >> check the collection name is "GitHub Jobs " >> Press import 
*Step F. Now you imported the collection >> Press on collection options (...) >> select run collection 
*Step G. After execution is finished >> you can open the console to view  the cleared results by entering (ALT+Ctrl + C) or from view menu 
*       

    

