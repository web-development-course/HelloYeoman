# Hello Yeoman
Follow this tutorial to create your first client application!

# Installations
- Google Chrome (<a href="https://www.google.com/chrome/browser/desktop/" target="_blank">download</a>)
- Sublime Text (<a href="http://www.sublimetext.com/" target="_blank">download</a>)
- GitHub (<a href="https://github.com/join" target="_blank">signup</a> & <a href="https://desktop.github.com/" target="_blank">download</a>)
- Node.js v4.2.3 (<a href="https://nodejs.org/en/" target="_blank">download</a>)
- Heroku Toolbelt (<a href="https://signup.heroku.com/login" target="_blank">signup</a> & <a href="https://toolbelt.heroku.com/" target="_blank">download</a>)

# Create the Application
- Open Node.js command prompt (windows) or the terminal (mac)
- Create a new folder (e.g. "Code") and cd into it
- Install Yeoman by typing `npm install -g yo`
- Create the project folder (e.g. HelloYeoman) and cd into it
- Generate the app by typing `yo webapp`
- Follow the instructions to create the default app
- Add the Procfile and web.js files from this repository to your project
- in the command prompt run `npm install gzippo express morgan --save`
- Build the app by running `grunt build`
- Run the local server by `grunt serve`
- Chrome will open in localhost:9000 and you'll see the app

# Make Some Modifications
- Open Sublime Text
- Open the `HelloYeoman` folder
- Open the `app` folder and click on the `index.html` file
- Change the text `Allo Allo` and change it to any text you want
- Save the file

# Connect to a Git Repository
- Open the GitHub desktop app, login with your account
- (Windows only) open the project directory in the command prompt and type `git init`
- Go to GitHub desktop and click the top left '+' sign
- Choose Add
- Select the HelloWorld folder
- Click 'Add Repository'
- Write a commit message (e.g. "First Commit") and click [Commit]
- Click the top right [Publish] button, then publish the repository
- (Windows only) click the top right [Sync] button to push the code
- Go to http://github.com and make sure that the repository exists with all the code

# Connect to Heroku
- Login to http://heroku.com
- Click '+' to create a new app (in the top right corner)
- Give it a unique name
- In the 'Deploy' tab, connect it to your GitHub repository
- Click [Enable Automatic Deploys]
- Go to Manual Deploy and click [Deploy Branch]
- Wait for the deploy to finish and click [View App]

# Hooray! You now have your first published client app
