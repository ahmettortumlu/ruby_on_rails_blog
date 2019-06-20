# README

At this application i created a blog using Ruby on Rails.

My main reference was : Mackenziechild's youtube video series which implementing blog application. You can reach this series link from : https://www.youtube.com/watch?v=nRyUn7D8zCc&list=PLqGj3iMvMa4JiH5mEBG4GNHWdC2u9xdzF&index=1

This app was also my first linux experimantal application and while comparing versus windows, Ubuntu was very simple to use and i encountered with less problem while importing required packs.


If you are new at Ruby on Rails like me, you  can use this link to installation for Ruby on Rails, it helped me without an error(using ubuntu 16.04): https://gorails.com/setup

I used

* RUBY VERSION
   ruby 2.6.3p62
   
* BUNDLED WITH
   1.17.3
   at the end steps i encountered with bundle gem error, i was using BUNDLE 2.0.2 and took "can't find gem bundler (>= 0.a) with executable bundle (Gem::GemNotFoundException) during bundle install with gem" error. When stackoverflow it i found the reason for the break in functionalities in bundler 2.0 is given in below mentioned link: https://bundler.io/blog/2019/01/04/an-update-on-the-bundler-2-release.html for stackoverflow link: https://stackoverflow.com/questions/54087856/cant-find-gem-bundler-0-a-with-executable-bundle-gemgemnotfoundexceptio/56646412?noredirect=1#comment99862943_56646412

* Database Creation

You can use SQLite (by default and not recommended), PostgreSQL and MySQL. But i used PostgreSQL(as recommended). While creating database i recommend you to not use password.


What my blog does?

* You can create post, edit and delete posts.
* Also there are navigation links at the top of the page. Naviggate simply
* I have home page and you can wee all posts at the home page.
