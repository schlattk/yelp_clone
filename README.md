## Overview

Clone of Yelp site using ruby on rails technology, raw practice version to practive setting up rails project

## Getting started

- git clone 'https://github.com/schlattk/yelp_clone.git'
- `gem install rails`
- `brew install postgresql` (extra configuration may be needed according to instructions)
- `bundle install` in the root directory
- `bin/rake db:create` to create the databases:'yrlp_clone_development' and 'yelp_clone_test'
- `bin/rake db:migrate` to run the database migrations


## Usage
- Run `bin/rails server` to run the Puma web server
- Visit `http://localhost:3000` to view the app in your browser

## Running tests
- Run `rspec` from the `/painLess` directory
- Currently shows `16 examples, 0 failures`

## Technology Stack
* Built using **[Ruby on Rails](http://rubyonrails.org/)**
* Uses a **[Puma Web Server](http://puma.io/)**
* Runs off a **[Postgres Database](https://www.postgresql.org/)**
* Tested using **[RSpec](http://rspec.info/)
