# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It is the file that runs your initial scripts and dependencies
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
It needs to be at the top level so that it runs on startup. It installs all of your libraries on run so that you don't have to inject them all individually.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
the standard console and the one provided in the app page on Heroku.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You have to make sure that your auth keys are set to heroku app instead of the just localhost
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It helps separate the work of other devs and you can revert changes if they are too extreme.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Every time code is pushed.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging.
```
