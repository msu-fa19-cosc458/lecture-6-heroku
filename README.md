# Heroku 
We need to push our site to Heroku so we can show it to the world! However, we have one problem. Heroku has space on their servers to host our code, but it has no idea how to run it or what to do with it (Note from Lecture 6 when it was stated we need to provision a server?)

With that being said, we need to push our code to Heroku's servers and also tell them how we want them to run our files. We do this via the 'Procfile' file and 'requirements.txt' file.

## Procfile
Procfile is a file used to tell heroku how to run your app. Just like AWS, you can only run one app at a time. For the project, you can only run from one app which means you need to either
1. Paste all your code in one file (which I strongly advise to not do as it can get messy)
2. Create classes for each of your APIs and pull them in via import.

For more information on Procfile, read the doc by heroku [here](https://devcenter.heroku.com/articles/procfile)
