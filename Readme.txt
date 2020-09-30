Commands that you will be needing during this project are as follows:


1) npm init     ( package.json will be created )
2) npm install express
3) npm install -g nodemon
4) nodemon server.js            (to run your server)
    (if this doesn't work)
    open windows powershell as admin and run following command
        i) Set-ExecutionPolicy RemoteSigned -Scope CurrentUser (more secured)
                            or 
        ii) Set-ExecutionPolicy Unrestricted
    It will run server now

5) npm install ejs
6) npm install uuid
7) npm install socket.io
8) npm install peer
    (if you have any problems with running video stream on google chrome then)
    1) Open settings on chrome from your desktop
    2) Click Shortcut button and append this following command
    --unsafely-treat-insecure-origin-as-secure="http://Localhost:3030"
    
    to the target bar. It will work fine now.

9) npm install -g heroku               (for deployment)
10) git init
11) git add .
    
    Meanwhile ,Make new file ".gitignore" and type "node_modules" on one line and 
    "Project Pictures" on other line

13) git init -m "Zoom clone"
14) heroku create                  (deployment starts here)

    you will asked to enter any key and press any key and log in to heroku account

15) git push heroku master
16) heroku ps:scale web=1
17) heroku open

   Your browser will be opened with a specific link
   Copy Paste this link and make your friends join the video call with you.
  
   My video link was: 
   https://peaceful-plains-78358.herokuapp.com/7b26c276-96f6-4bf7-92ec-3eb7fd90add8


Big Thanks to Clever Programmers for making this happen.
Happy Coding!
