# How to host your first site for free with Google Firebase

**A step by step tutorial**


1. To begin, we're going to go ahead and fire up our IDE of choice, in my case VS Code, and open a new folder. <br><br>

2. Once we are in our new folder in VS Code, we're going to open up our terminal and run the following command in order to install firebase tools globally <br>
`npm install -g firebase-tools` <br><br>
3. Once this is installed we can get our hosting setup with the following set of commands <br>
`firebase login` <br>
This will prompt us to sign in with the Google account that we created the project with <br><br>
`firebase init` <br>
After running this command we will want to go down and select the hosting option to configure foles for Firebase Hosting, as seen below <br><br>
![Alt text](image.png) <br><br>
We will then be prompted to either use an existing project or create a new one, and we're going to go ahead and create one.
![Alt text](newProject.png) <br><br>
Give your new project an ID and name, and specify the public directory (can just leave as public by pressing enter) we will just have a few more questions to answer. <br><br>
![init](init.png) <br><br>
For now answer no to single-page app and automatic builds with Github, and we will be done initializing our new project. <br><br>
4. All that's left to do at this point in the process is to deploy our new site!
<br>Use the following command <br>
`firebase deploy` <br>
and our new site should be live! <br><br>
<br>
You can view an example of a completed setup at the following domain https://examplefirebase8888.web.app/