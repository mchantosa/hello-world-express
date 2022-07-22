# hello-world-express
## An introduction to Express

This project is a more complex intro to Express than [first-express-app](https://github.com/mchantosa/first-express-app).

**Examples:**

* **Setting up templates:** specified and created `view` directory to hold `*.pug` templates
* **Integrated static assets:** added a `public` directory with images and stylesheets
* **Extending a template:** extended `layout.pug` to english, french, serbian, and thai templates
* **Established handlers to pair routes to views** 
* **Added navigation**
* **Added logging:** through use of morgan middleware module
* **Consolidated code through use of helper functions and variables:** function `app.locals.currentPathClass` defined in `hello.js` becomes available to views
* **Set language attribute in html tag:** both language and region [reference](https://gist.github.com/JamieMason/3748498)
* **Consolidated code with loop within template:** navigation in `layout.pug`
* **Introduced route parameters**
* **Added error handling:** through the introduction of middleware
