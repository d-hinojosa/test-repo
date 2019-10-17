---
title: "codeacademy"
---
# Road to Hire 
## Note Taking App

### Deploying your Full Stack app to the internet

1. clone the noteapp

```js
git clone https://github.com/pdhoward/noteapp.git
```

2. Follow the usage instructions to install and run the app on your desktop

3. Carefully review the set of instructions regarding deployment of a full stack app to the cloud, including
    * deploying your app to a repo in your github account
    * creating heroku and mongodb atlas accounts
    * creating a heroku cli
        - your best friend will be: `heroku logs --app=<appname>`
    * creating a database and connection on atlas
    * whitelisting a universal ip address on atlas
    * creating a user, password and readwrite privledges for your api on atlas
    * copying your app connection string and updating it for user and password
    * testing your app locally using atlas   
    * creating a heroku app
    * connecting the app to your github account (continuous deployment)
    * verifying proper structure for deployment
        - devdependencies
        - npm scripts
        - node engine
        - acquiring port and uri via gloabl process object
    * setting a heroku config variable (.env on the cloud)
    * reviewing heroku dashboard on activity
    * open the app on heroku

4. Note: Your challenge submission should be the link to your professionally composed github repo for your completed app. Your github repo should include the link to your live app on heroku!