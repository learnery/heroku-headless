[![Build Status](https://secure.travis-ci.org/moredip/heroku-headless.png?branch=master)](http://travis-ci.org/moredip/heroku-headless)
[![Dependency Status](https://gemnasium.com/moredip/heroku-headless.png?travis)](https://gemnasium.com/moredip/heroku-headless)
[![Code Climate](https://codeclimate.com/github/moredip/heroku-headless.png)](https://codeclimate.com/github/moredip/heroku-headless)

# HerokuHeadless

## What?
Push from your git repo to a heroku app without any external configuration.

## Why?
Heroku's workflow is geared towards pushing to a heroku app from a dev workstation. This gem makes it easy to push to a heroku app as part of a CI/CD setup.

## Installation

Add this line to your application's Gemfile:

    gem 'heroku-headless'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install heroku-headless
    
## How do I use this?
It's as simple as
```ruby
require 'heroku-headless'
HerokuHeadless::Deployer.deploy( 'your-app-name' )
```

## Tell me more!

[Deploying To Heroku From CI](http://blog.thepete.net/blog/2013/01/21/deploying-to-heroku-from-ci)

[Deploying to Heroku From CI - the Gory Details](http://blog.thepete.net/blog/2013/01/22/deploying-to-heroku-from-ci-the-gory-details/)
