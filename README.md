#README FOR APP ENGINE ESSENCE

##What is this?
App Engine Essence is a development foundation to get your idea up and running on Google App Engine as quickly as possible, while still looking stylish.

###Front end
You know how new born babies can [look as gruseome as Freddy Kruger](http://cdn2.holytaco.com/wp-content/uploads/2011/01/455813-Copy.jpg) but everyone still says how cute they are?

Nobody says that about web applications. It doesn't matter how awesome your code is or how intricate the problem is you just solved, end users only care if it 'looks nice'. Once they get past the smoke and mirrors they begin to glimpse just how fantastic your work is.

The [Twitter Bootstrap (v2.0.2)](http://twitter.github.com/bootstrap/) is integrated because I'm a programmer and not a designer, and I'm tired of spending time trying to figure out what looks good or not: TB allows me to concentrate on building great stuff rather than apologising about how it looks!

###Back end

This project is based on the great work by the App Engine Boilerplate team, but I have other ideas and needs. As such, App Engine Essence is opinionated and built to primarily accomodate what I use most.

I'm very happy to listen to ideas, recommendations or constructive criticisms, but I would love to see how you use it!

##What does it include?
- An extensively modified fork of the [App Engine Boilerplate](http://www.appengine-boilerplate.com/)
- Use of <code>[webapp2](http://webapp-improved.appspot.com/)</code> allows you to take advantage of the `python27` runtime, threading, sessions, named routes and more!
- [Twitter Bootstrap (v2.0.2)](http://twitter.github.com/bootstrap/): provides an attractive front-end so your app looks good from the outset (concentrate on awesome code)
- [Modernizr 2.5.3](http://modernizr.com/): I encourage you to grab your own version of Modernizr with just the features you need for you particular app. The one included here tests for most things and include `.load()`
- [Google Analytics](http://www.google.com/analytics/) placeholder: doesn't render on local dev to improve speed and and not interfere with your statistics
- [Font Awesome](http://fortawesome.github.com/Font-Awesome/): Iconic font designed for use with Twitter Bootstrap
- [OpenID](http://openid.net/) authentication with a beautiful interface
- [MailChimp](http://mailchimp.com/) integration
- Decorators: `@login_required` & `@admin_required`
- Template filters: `truncate_chars`, `short_url` & `prefix_cdn`
- Out of the box support for **sessions** & **named routes**
- Caching framework
- Page not found (404) handler and page
- User preferences model with caching and [Gravatar](http://www.gravatar.com/) image
- Best practice site configuration defaults

##What does it not include?
- [HTML5 Boilerplate](http://html5boilerplate.com/): This is a fantastic piece of work, but if you are like me and you are a programmer and not a designer, it doesn't help make your app look nice!
- Build script to optimize images, js and css files. H5BP extracted this to it's [own repo](https://github.com/h5bp/ant-build-script) so you can include it and configure it if you want.

##What does it assume?
- You can, or want to program Python
- You can, or want to program and deploy for App Engine
- You know how, or want to program web apps
