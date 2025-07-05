# README

- [References](#references)
- [Quick start](#quick-start)
- [Versions](#versions)
- [Things to cover](#things-to-cover)

## References

- [Ruby on Rails](https://rubyonrails.org/)
- [https://github.com/rails/rails](https://github.com/rails/rails)

## Quick start

From [https://github.com/rails/rails](https://github.com/rails/rails):
```
$ gem install rails
$ rails new rails-playground
$ cd rails-playground
$ ./bin/rails server
```
**./bin/dev** can be used instead of **./bin/rails server**:
```
$ cat bin/dev
#!/usr/bin/env ruby
exec "./bin/rails", "server", *ARGV
```

> At this point you can go to [http://localhost:3000](http://localhost:3000) in your browser

Using information to the beginnig of [https://rubyonrails.org/](https://rubyonrails.org/) → [https://d2biiyjlsh52uh.cloudfront.net/rails/rails-8-demo.mp4](https://d2biiyjlsh52uh.cloudfront.net/rails/rails-8-demo.mp4) scaffold **post** with **title** and **body**:
```
$ rails generate scaffold post title:string body:text
$ rails db:migrate
```
> At this point you can go to [http://localhost:3000/posts](http://localhost:3000/posts) in your browser and start using the app.

## Versions

From [http://localhost:3000/](http://localhost:3000/) when **./bin/rails server** is running:

- **Rails version**: 8.0.2
- **Rack version**: 3.1.16
- **Ruby version**: ruby 3.2.3 (2024-01-18 revision 52bb2ac0a6) [x86_64-linux-gnu] \
  I'm using **Linux Mint 22.1**

## Things to cover

List originally created by **rails new rails-playground** command:

* Ruby version
* System dependencies
* Configuration
* Database creation
* Database initialization
* How to run the test suite
* Services (job queues, cache servers, search engines, etc.)
* Deployment instructions
* ...
