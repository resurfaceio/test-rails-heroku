# test-rails-heroku

This was cloned from Heroku's [Getting Started with Ruby on Heroku](https://github.com/heroku/ruby-getting-started) app at commit `fc36262`. We prefer to keep our own copy to keep our tests from breaking without warning.

To run locally:

```
brew services start postgresql
createdb ruby-getting-started_development
rake db:migrate
heroku local
```
