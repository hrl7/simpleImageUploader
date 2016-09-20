# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

```
rails -v
rails new -B ImageBoard
cd ImageBoard
git init
gibo -u
gibo vim rails macos >> .gitignore
git add .gitignore
git commit -m "add gitignore"
git commit -m "add rails project"
vim Gemfile
bundle
git commit -m "add gems"
rails g scaffold post comment:string user:string image:string
rake db:create
rake db:migrate
vim config/routes.rb
git add .
git commit -m "add posts"
rails g
rails g uploader
rails g uploader Image
vim app/models/post.rb
ls
vim app/views/posts/_form.html.erb
rails s
vim app/views/posts/show.html.erb
git commit -m "add image uploader"
tig

```
