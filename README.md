# Postman-QAChallenge

 Steps to run collection in 2 ways  : <br />

S1. Download and intall postman through the below link: <br />
    https://www.postman.com/downloads/ <br /> <br />
S2. Install the postman after downloading is copmpleted <br />

--> Hint: Sign in to postman to never loose you progress <br />

*********************************** [ 1st way]**************  run from Command prompt************************** <br />
Step A. Open CMD (Command runner ) <br />
Step B. Download and install Node js version which is compatible with your machine: <br />
        https://nodejs.org/en/download/current/ <br />
Step C. Follow the bellow commands to run th e targeted collection from CMD: <br />
        By installing Node js in step B  >> Newman is just a command away. Install Newman from npm globally on your system, which allows you to run it from anywhere. <br />
        
       Run the following :  <br />
       npm install -g newman    .....(Press enter )   <br />
        
        
       The easiest way to run Newman is to run it with a collection. You can run any collection file from your file system. <br />
       To  run  the collection :
       newman run https://www.getpostman.com/collections/df353dd6162705203daa   -n 3             .....(Press enter )   <br />
       
       Hint: -n, --iteration-count [number]	Define the number of iterations to run , you can change it bu just change the number after -n  <br />
        
        
*********************************** [ 2nd way]**************  run from Postman ************************** <br />
    
Step A. In postman Press file option  <br />
Step B. Press Ctrl +O or press import... <br />
Step C: In the pop-up >> Press link tab  <br />
Step D: Paste the following collection link: <br />
        https://www.getpostman.com/collections/df353dd6162705203daa <br />
Step E. Press continue >> check the collection name is "GitHub Jobs " >> Press import  <br />
Step F. Now you imported the collection >> Press on collection options (...) >> select run collection  <br />
Step G. After execution is finished >> you can open the console to view  the cleared results by entering (ALT+Ctrl + C) or from view menu  <br />
       

    

