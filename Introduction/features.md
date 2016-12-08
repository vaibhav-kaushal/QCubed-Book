# Features

Oh yes, the interesting part - features. The part where I tell you why on earth should you download, install, learn, practice yet another framework and go through all the pain. Here are the features of QCubed. Go through it and let us know if it is worth the pain. Here is the list:

## MVC
Time tested and universal - the MVC pattern can be easily called the king of all design patterns for making any standard app - web, mobile, desktop etc. 

*If you do not know what MVC is, you can learn about it [here](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller).*

QCubed follows MVC. That being said, it will allow you to break the pattern (not recommended, but when you need to, you should be able to). As you progress, we will show you how QCubed handles it better than most other frameworks. 

## Stateful Programming
Web, by its very nature is stateless. QCubed however is built in a way that allows you to build on top of that stateless chaos and program your pages as you would program a Desktop App or a Mobile App. The QForms library saves states on the server and the pages you create using QForms automatically transmit the state of each page with each request and handle all the transitions for you. 

## Mastering JS is an option
When it comes to the web, JS is the language for the browser. For making any website which behaves well, you are going to need to learn JS and implement it on the frontend. 

Unless we are talking cool animation and frontend tricks, QCubed makes no assumption that you are great with JS. Why? Because all the common JS related functions - making stuff disappear and re-appear on the page, submitting AJAX request, redirecting, showing a message sent by the server etc. are all handled automatically for you. 

You write the event handlers for your front-end actions and QCubed automatically creates all the JS and applies it to your web page. Well, it actually writes jQuery commands but you don't have to worry about that.

## Database support
Chances are high that you are going to start with some open source database. QCubed supports most of them. MySQL and PostgreSQL are supported the best. SQLite is supported for the small apps which can do without a full blown server. If you are a Oracle or Microsoft SQL server lover, they are supported as well.

## Caching
Caching is done on different levels. QCubed has caching support for the fowllowing: 

1. File based 
2. Memcache based
3. PHP based single script run caching

If you need multilevel caching e.g. You want to cache using PHP based caching which is then backed by Memcache which falls back on the database - you have the option to. 

It also generates code which can *automatically* cache your Database objects. You just have to turn the switch on. Speaking of Database objects, we have a great Code Generator.

## Code Generation
This is one of the most unique features of QCubed