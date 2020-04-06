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

* ...

## Running rails server
`rails server`

## Troubleshooting
### Installing Rails
Run the command 
`rails -v` 
to check if rails is installed or not. 
If not run the command 
`gem environment` 
Export the PATH variable in your .bash_profile as per the mentioned path of the EXECUTABLE DIRECTORY. Then try to run rails again.

### Running Rails server
```
brew install yarn
rails webpacker:install
yarn install --check-files
rails s
```

### Creating Controller and View

To create a new controller, you will need to run the "controller" generator and tell it you want a controller called "Welcome" with an action called "index", just like this:
```rails generate controller Welcome index```
This generates the following files:
assets/stylesheets/welcome.scss
controllers/welcome_controller.rb
helpers/welcome_helper.rb
views/welcome/index.html.erb


