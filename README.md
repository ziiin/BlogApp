This is a web application built on rails framework. Provides facility to create
blogs and put comments over that blog.

Steps to creation of this app(How did I ??):

Create a rails project with desired name:
 " rails new BlogApp "

=======================================

This creates alot of stuffs:
app => Model View and controller code
bin => Helper scripts ( bundle, rake, rails)
config => App, database and route configuration
db => Database schema and migrations
Gemfile => specify requited gems
log => App logging directory
public => Webroot of the application
tests => test suits for the application

=======================================

Use scaffold to generate MVC for posts and comment

For post : " rails generate scaffold post title:string body:text "

For comment : "rails generate scaffold comment post_id:integer body:text"

=======================================

Create the post and comment database tables
" rake db:migrate "

=======================================
