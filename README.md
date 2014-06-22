HelloHeroku
===========

hello world with heroku and node.js, just gettin' my feet wet. hadn't tried heroku yet, considering using it for a project - so tried the tutorial over at https://devcenter.heroku.com/articles/getting-started-with-nodejs

running at http://quiet-ocean-2599.herokuapp.com/

If your machine is having difficulty recognizing heroku, foreman and ruby commands, try the following:

  1. Install the Heroku toolbelt at C:/Heroku (choose custom install, and uncheck foreman)
  2. Uninstall the Ruby that Heroku toolbelt installed and use the windows installer - make sure you check the PATH option during setup
  3. Add foreman to your node package.json devdependencies and do an npm install
  4. Edit the Express version in dependencies to ~3.2.6, foreman didn't like 4.4.4
  
