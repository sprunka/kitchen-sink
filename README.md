# Cooking With PHP:
## A Foodie's Guide to Learning OOP (via MVC)

+ **OOP** is Object Oriented Programming.
+ **MVC** is Model, View, Controller. (plus extras like helpers and libraries)

CAVEAT: Anthony "ircmaxell" Ferrara wrote a great break down of [MVC concept vs. pattern](http://blog.ircmaxell.com/2014/11/a-beginners-guide-to-mvc-for-web.html "Read this first.") and why you probably should not learn MVC.

So go read that post, I'll wait. ... ....

Great post, right? So why am I teaching it if you shouldn't bother learning it? Well, right now, this tutorial is in flux. I'm growing as I'm creating it. So maybe by the time it goes public it won't involve "MVC". This tutorial is all about helping you learn about OOP. This interpretation of the MVC concept was my introduction, so it is what I currently know best.

On with the show!

Models are our containers. They hold stuff. Compare to tupperware. In our case they'll hold ingredients. Sometimes they are more like the pantry, holding other containers.

Views are all about presentation. They are both the plate and that fancy person that decorates and makes everything look awesome.

Controllers are like a mixing bowl, you put your stuff in there when you want to do something with/to it. Then after you've done something, you dump it on a plate.

This leaves the helpers/libraries. This is where most of the cooking gets done. Everything from chopping to mixing to heating or cooling.

Because everyone should write their own framework once (and then throw it away) the aim of this project is to be a guided tutorial to build a lightweight MVC framework in order to acclimate the students into a familiarty with OOP.

This project intends to follow [PSR-1](http://www.php-fig.org/psr/psr-1) and [PSR-2](http://www.php-fig.org/psr/psr-2) for coding standards and style; as well as [PSR-3](http://www.php-fig.org/psr/psr-3) for logging and [PSR-4](http://www.php-fig.org/psr/psr-4) for autoloading, but indepth explanations of these guidelines is outside the scope of the tutorial. You are encouraged to [read up on PSR](http://www.php-fig.org/) on your own time.

The `master` branch will always contain the project at its baseline. A skeleton of folders with placeholders. Each segment of the tutorial will have its own branch from the previous.

+ TODO: add a vagrant box. (apache 2/PHP 5.6)
+ TODO: add Course Outline
