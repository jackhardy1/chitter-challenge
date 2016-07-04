[![Build Status](https://travis-ci.org/jackhardy1/chitter-challenge.svg?branch=master)](https://travis-ci.org/jackhardy1/chitter-challenge)

[![Coverage Status](https://coveralls.io/repos/github/jackhardy1/chitter-challenge/badge.svg?branch=master)](https://coveralls.io/github/jackhardy1/chitter-challenge?branch=master)

Chitter Challenge
=================

Makers Academy - Week 4 weekend Challenge

Aim: To build a twitter clone, where users can sign up, log in, and create their very own peep.

#### Technologies Used
- Ruby
- Sinatra
- PostgreSQL
- RSpec

#### Intallation instructions

```
install postgreSQL, then from the command line run the following:
$ git clone https://github.com/jackhardy1/chitter-challenge
$ bundle
$ createdb chitter_development
$ rake db:auto_migrate
$ rspec
$ rackup
```

#### Features
-------

```
As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

As a Maker
So that I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made
```
