# Simple Parse Javascript WebApplication

Simple introductory backbone.js application and then some minor changes are made to it so that it works with Parse, and its data store backend.

### Video
Here is where the sample backbone app is taken from. And a nice intro to Backbone.js  
  
[![Backbone.js Tutorial-Beginners](http://img.youtube.com/vi/FZSjvWtUxYk/0.jpg)](http://www.youtube.com/watch?v=FZSjvWtUxYk)

### Setting up Parse

* Go to [Parse.com](https://www.parse.com/apps), create a new app and get your *Application Id*, and *Javascript Key*.
* Make a new copy of **config.js.copy** and name it **config.js**
* Fill your keys in **config.js**
* Go to your apps dashboard and then click on Data Browser tab. You can find it here https://www.parse.com/apps/YOUR_APP_NAME/collections
* Create a new class named *Person*. And add additional rows named *age*, *firstname*, *lastname*.
* If you wish you can create sample *Persons*.
* ``` python -m SimpleHTTPServer 8080 ``` in your current folder to start a simple python server.
* Go to *localhost:8080* on your browser to see your simple Parse app.