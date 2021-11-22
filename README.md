# Python Django Codebase

### <center><span style="color:#B33A3A;">Before you send any python code, please, make sure you follow Google Python Style Guide !</span> (https://google.github.io/styleguide/pyguide.html)</center>

## Technology Stack we'd like to have in the end
* **Python 3.7+ and Django 3** [REST, ORM, full authentication systems support (Google, JWT, OAuth2)].
* Frontend implementation, just use HTML5/SASS/**Vue.js**/React. The simplier the better (don't use all sort of bells and whistles script kiddie tools).
* Mysql and MongoDB ready-made connectors.
    * maximum efficiency for database (well implemented indexes, tuning) | prepare report (including statistics) what we can expect in terms of speed of our database
    * decide when client would need Mysql and when MongoDB (pros and cons)

## Views we need to implement first
* Implement backup system | page should have really small footprint and easy to restore in every single moment.
* Login form and entire user authorization and authentication logic (admin user and employee at the very least)
    * nice and secure 'forgot password' implementation
* WYSIWYG editor | simple image editor | mechanism to display good-quality photos in any size we would need
    make possible to create a simple page by customer using .txt file
* All data stored in JSON or YAML (if it is created by user manually)
* Make you code fully asynchronous, use HTTP 2.0, 
* Custom routing mapping | SEO support for clean google results
* Design a system that can map the entire web page (with JS, python etc.) to JSON
    * e.g. you can download all notes and posts in a single query and transfer it to Linux X Server GUI application or mail to your customer
* Pages should implement fully I18 tranlation systems
* Send e-mail | plugin to integrate your e-mail client with web page tables (dashboard?)

## Selected work for Paweł's (frontend stuff)
* Dashboard welcome page implementation (can we use https://vuejs.org/resources/themes.html?)
    * nice table representation (mixed-up JS plugins should be enough) | nice database integration with filtering
    * statistics widgets
* Nice looking forms (we need to create custom library with amazing widegts for every form element which is currently available)

## Selected work for Tomasz's (docker and bash autmatization stuff)
* all should be based on containers (Docker)
* bash script to create a single web page instance with ready template working as POC

## [TODO] Note-taking System
I need a HTMl canvas working as a text editor. Basically, user should be able to enter any text (let's assume we have a student writing markdown file with summary of his stydy session). Application should implement text selection and have an option to shorten selected text and tranform it in a box with text. https://css-tricks.com/wp-content/uploads/2018/10/flex-wrap.svg
