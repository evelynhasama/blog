# README

Based on https://guides.rubyonrails.org/getting_started.html
Steps through 1 - 7.2

commands:
```
bin/rails server (connects to http://localhost:3000/)
bin/rails generate controller Articles index --skip-routes (generates controller and actions)
bin/rails generate model Article title:string body:text (generates Article data model)
bin/rails db:migrate (migrates datebase)
bin/rails console (launches console)
article = Article.new(title: "Hello Rails", body: "I am on Rails!") (initilizes new article)
article.save (saves article)
```
