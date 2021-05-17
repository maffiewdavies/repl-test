# repl.it-govuk-prototype-kit

This template is intended to support runnig the [GOVUK Prototyping Kit](https://govuk-prototype-kit.herokuapp.com/) on devices that won't allow for a traditional install. It uses repl.it, a cloud based environment to host, edit and deploy your prototype.

## Getting started

1. Ensure you have a [GitHub](https://github.com/) account
2. Create a free [repl.it](https://repl.it/) account and connect it to your GitHub account
3. Make a copy of this repo (repl.it-govuk-prototype-kit) by clicking the **Use this template** button at the top of the page
4. Give your new repo a descriptive name
5. Open repl.it and create a new repl
6. Choose 'Import from Github' and select the repo you created at step 3 and let repl clone the repo

## Once the project has been added to repl.it we need to set it up

1. Click 'Run' at the top of the page and let repl.it install a bunch of things. This will take a few minutes. 

If you this error: `ERROR: Node module folder missing. Try running npm install`, type `npm install` into the Consle window and press enter.
 
2. Pay attention to the Console window. You will know that the installation is nearly finished if it asks you *"Do you give permission for the kit to send anonymous usage data? (y/N)"*
3. Type *y* or *n* and press enter and wait for it to finish building your prototype
4. You will know if the setup is finished when a window showing your prototype appears, yessssssss!! ✨  
5. We recommend you create a username and password for your prototype. Do this by editing the existing .env file. Add the [following code](https://gist.github.com/jesseyuen/fa7743da8a1e7d3082c6319326744054) to the bottom of your .env file, ensuring to personalise the username and password values

## Once the project is running

1. You can skip past the [Prototype kit install docs](https://govuk-prototype-kit.herokuapp.com/docs/install), repl.it has done this for you
2. Start learning how to [Build a basic prototype](https://govuk-prototype-kit.herokuapp.com/docs/make-first-prototype/start)

## Once you've made changes to your project

1. If you're happy with your changes, commit and push your work back to your GitHub repo using the repl.it *Version Control* feature in repl.it
2. You're off and away!

----

## Things to be aware of

The prototype kit docs refer to `localhost` urls. Repl.it uses it's own url structure so whenever you read `localhost/blah` in the docs you need to think `repl.it-url/blah`. 
