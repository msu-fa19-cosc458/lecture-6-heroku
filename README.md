# Heroku 
We need to push our site to Heroku so we can show it to the world! However, we have one problem. Heroku has space on their servers to host our code, but it has no idea how to run it or what to do with it (Note from Lecture 6 when it was stated we need to provision a server before it can run our code?)

With that being said, we need to push our repo (with our code) from AWS to Heroku's servers, and also tell Heroku how we want them to run our files. We do this via the 'Procfile' file and 'requirements.txt' file.

## Procfile
Procfile is a file used to tell heroku what command to run your app from their terminal. Just like AWS, you can only run one app at a time. For the project, this means you need to either
1. Paste all your code in one file (which I strongly advise to not do as it can get messy)
2. Create classes for each of your APIs and pull them in to your main python file via import.

For more information on Procfile, read the doc by heroku [here](https://devcenter.heroku.com/articles/procfile)

## requirements.txt
Requirements file tells Heroku's servers what external libraries need to be installed. Personally, I just throw in all the names of the libraries I imported via my python files on AWS... because I'm too lazy to figure out what version of linux Heroku runs and what python libraries are already pre-installed.
