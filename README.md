### The Complete Node.js Developer Course - Node Web Server (Udemy: Andrew Mead, Section 5)

https://github.com/ARWL2016/node-web-server 

#### Technology  
1. Express - basic routing
2. Hbs (handlebars plugin for express) - with partials and helpers


#### HBS Templating Engine   
1. We can include a partial (an html fragment) in an hbs page with `{{> header}}`.  
2. We can create functions with the `hbs.registerHelper()` method. See server.js.   
3. To use hbs, require the module and set the view engine.  
4. Use `hbs.registerPartials()` and pass in the url to use partials. 
5. In this app, we do not have `app.use('views', 'url')` because the hbs file are in the default `views` folder

Note that an alternative module *express-handlebars* is used in Jonathan Mills Node course on Pluralsight, but the setup is not as simple as hbs. 

