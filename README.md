Rhiya Teres Sebastian
Student ID: 8715261

Instructions to deploy on heroku:
1) After the code is committed to GitHub, open a free account on Heroku on this link:https://signup.heroku.com/login
2) Once you have your account ready, login with your credentials.
3) Click New on the top right corner and select “Create new app”.
4) Give your app a name (This will be included in the public URL for your application) and click Create app.
5) This step will take you to the dashboard of your app. Open Deploy tab and scroll to the “Deployment method” section. Select GitHub as the method.
6) It will show a “Connect to GitHub” option where we can provide our GitHub repository. If you are doing it for the first time, Heroku will ask permission to access your GitHub      account.
7) You can search for your GitHub repository and click connect.
8) If it’s able to find and connect to the GitHub repository, the Deployment section will show up where you can select if you want Automatic Deployment (as soon as the changes are    pushed to GitHub, Heroku will pick them up and deploy) or Manual Deployment.
9) Click Enable Automatic Deploys.
10) Open the Settings tab and locate Buildpacks and click “Add buildpack”.
11) Select php from the options and click Save changes.
12) Now, go back to the Deploy tab, and click Deploy Branch at the bottom. Heroku will take the code and host it.
13) Open the Activity tab and there you can see the progress.
14) Open the settings tab and scroll down to the Domains and certificates section. Here, you can see the URL of your app that was just deployed. Copy and paste that URL in the browser.
