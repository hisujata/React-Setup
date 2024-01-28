Here is how you can you set up your first react app to get the react jouney going!

When I started learning react I had issues with getting the setup ready. I had spent a lot of time on google, watch videos on youtube but it was time consuming. Hence created this step by setp guide to get the setup ready.

Prerequisite that you need

    1. visual studio
    2. node js
    2. npm
    3. npx

link to download visual studio code is below

https://code.visualstudio.com/Download

Download the recommended version of node js the link to install is below

https://nodejs.org/en

Commands

Open the terminal window and give below commands to check if everything is installed properly

    node -v
    
    npm -v
    
    npx -v

If so far everything is going fine then npm -v command is should show you the versions of the packages you installed. Now you are all set to create your reat app.

Give below commands the create the app


    npm install -g create-react-app

    npx create-react-app CustomName

Give a CustomName to your app whatever you like. If everythig goes weel then you will see "webpack compiled successfully" on your terminal window. That means you succeeded at creating your first react app. Now give below command to get the app started to run the app.

    cd CustomName

    npm start 

<img src="https://github.com/hisujata/React-Setup/blob/master/screenshot.png">

By dfault the app runs on port 3000. Now you wont be able to type anything in terminal but dont worry thats happening as its running the code on web. 
You can open a new terminal window in vs code by clicking + sign to start operating on this app. 
However if not able to do anything on terminal window overwhelms you then press ctrl+c but this will also stop the app which is running on browser. So the best practice is to open new terminal window for futher modification or downloading any other packages as per your project needs.

Happy Learning!

