A Blog From Scratch
===================
  
----
:construction: UNDER CONSTRUCTION :exclamation:
:vertical_traffic_light: STATUS: Setting Up Environment

----


I'm going to attempt making a blog from scratch that I can hopefully attach to my website.. that I will create in the future (:
 
## The Process
### Setting Up the Environment
1. Make _package.json_ file creating dependencies (Mongoose, Express, EJS, etc.. )
  - The private flag ensures that our site doesn't get accidentally published to the npm directory.
2. install all dependencies set up in _package.json_
  - `npm install`
3. `express --sessions --css stylus --ejs`
  - this creates express MVC like subdirectories with session, stylus, and ejs
4. `express --css jade`
  - forgot to add jade (:
5. Install nodemon to watch for changes to the application while it's running
  - `npm install -g nodemon`

## Notes
+ APP.JS

### Order Of Operations
1. User navigates to a URL
2. Browser sends the get request to the application (siteurl.com/users)
3. then _app.js_ (which is like the route file) handles the get request
  - app.get('/url', function); **_example:_** _app.get('/users', user.list);_
    - user.list
      - user = a variable set up in the begininng of _app.js_ that links to a javascript file in the _/routes_ folder (_user.js_)
      - list = a function that was set up in _/routes/user.js_ and **exported** to be used other places
        - this function takes a request (don't know what to do with that yet) and a response and can do a few things (send, render, & other things i don't know yet)
  
## Resources Used
- [Express Tutorial](http://expressjs.com/guide.html)
- [Markdown Github Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Github Emojis](http://www.emoji-cheat-sheet.com/)
- [Pagination](http://drupal.org/project/pagination)

### Other Things I came across...
#### Development
- [Express Node Structure](http://dailyjs.com/2012/01/26/effective-node-modules/)
- [Understanding Resources](http://www.mattpalmerlee.com/2012/11/09/getting-started-with-node-js-express-and-jade-using-the-webstorm-ide/)

#### Design
- [Gemojis](https://github.com/github/gemoji)
- [Markdown Syntax](http://en.wikipedia.com/wiki/Markdown)
- [Social Media Icon Pack](http://www.komodomedia.com/blog/2009/06/social-network-icon-pack/)
- [Social Sign In Buttons](http://www.komodomedia.com/blog/2009/06/sign-in-with-twitter-facebook-and-openid/)
- [Sexy Music Overlays](http://www.komodomedia.com/blog/2009/03/sexy-music-album-overlays/)
- [Gallery Slideshows](http://www.1stwebdesigner.com/css/57-free-image-gallery-slideshow-and-lightbox-solutions/)
- [Inset Icons](http://glyphicons.com/)

  	
## Questions
+ here


## Goals 
+ Integrate blog with personal web site and portfolio
+ Labs section
  - Blog by itself
  - Stock Brackets 
  - 2 Person mobile tic tac toe
    - use socket IO 

  
<br> 
> (git remote set-url origin git@github.com:Folashade/blogFromScratch.git)

