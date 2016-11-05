Sinatra Template Application

Description
===========

Simple sinatra application template with rspec, capybara and simplecov.

Running
=======

If you don't want to be limited to the versions in the Gemfile.lock, remove it before `bundle install`

```
bundle install --path ./vendor
bundle exec foreman start
```

Testing
=======

Tests with rspec.

```
bundle install --path ./vendor
bundle exec rake
```

License and Author
==================

- Author:: Chris Horton (<hortoncd@gmail.com>)
- Copyright:: 2016, Chris Horton

This app is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT) as listed in the included LICENSE file.
