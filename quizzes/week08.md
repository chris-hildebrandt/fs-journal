# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json file defines the dependencies that should be installed with your application. it needs to be at the root level of the app. To create a package.json file for your app, run the command npm init in the root directory of your app. It will walk you through creating a package.json file. this file is required because it declares the apps dependencies and allows the app to download those dependencies without which, of course, your app will not function properly.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env.js and .env
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
branch merge
```