# Messenger

## Description
This is a simple project that follows along with the [Simple Messaging App](https://github.com/TheOdinProject/curriculum/blob/main/ruby_on_rails/mailers_advanced_topics/actioncable_lesson.md) to learn how Action Cable can be used to enhance an application to give it real time features.  
This app was built in two stages:
1. The first stage was an app for sending messages only viewable to those currently logged in.
2. The second stage was to build on the first stage to save the messages so that they are also visible to anyone who logs in later.

## Gems
This uses the Devise gem for authentication and the bulma-rails gem for styling.

## Ruby and Rails
The Ruby version is 3.2.2 and the Rails version is 7.0.6  
To view your system versions use `ruby -v` and `rails -v`

## Setup
If you'd like to rub this app yourself follow these steps:
1. Clone the repo `git clone https://github.com/kguyer/messenger`

2. cd into the project `cd messenger` 

3. Migrate the database `rails db:migrate`

4. Seed the database with the seeds from db/seeds `rails db:seed`

5. Start the server, `rails server`

6. Visit `localhost:3000` in your browser