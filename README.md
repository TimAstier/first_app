# Forest Rails Liana

Forest is a modern admin interface (see the [live demo](https://app.forestadmin.com/login?livedemo)).   
This admin interface is available for projects of all major web frameworks.  
forest-rails gem is the liana (=connector) that makes Forest admin work on any rails app.

## Installation

Visit [Forest's website](http://www.forestadmin.com), enter your email and click "Get started".  
You will then follow a 4-step process (also available in this 1 min [video](https://www.youtube.com/watch?v=CaGBAV1T944)):

1. Choose your stack (Rails)
2. Install Forest Liana
  ```ruby
  ## Add to your application's Gemfile:
  gem 'forest_liana'

  ## Bundle it
  bundle install

  ## Install it
  rails g forest_liana:install

  ## When prompted, enter the provided secret key
  YOUR-SUPER-SECRET-SECRET-KEY
  ```
3. Get your app running, provide your application URL and check if you have successfully installed the Forest Liana on your app.  
4. Choose your credentials, log into https://app.forestadmin.com and start customizing your admin interface!

## How it works

Installing forest-rails into your app will automatically generate an admin REST API for your app.  
This API allows the Forest admin UI to communicate with your app and operate on your data.  
Note that data from your app will never reach Forest's servers. Only your UI configuration is save on Forest's server.  
As this gem is open-source, you're free to extend the admin REST API for any operation specific to your app.  

## Integrations

One core concept of Forest is to bring all your data back into one single admin interface.  
Forest integrates with the 3rd party services / SaaS you already use and allow you to manage all your operations from one place.

Here are the integrations currently supported:
* Stripe
* Intercom
* Zendesk
* Close.io

Note: More integrations will be developed given on users' requirements.

## Documentation

Complete documentation is available on http://doc.forestadmin.com   
Documentation and this liana are officially maintained by Forest.

## Licence

[GPL v3](https://github.com/ForestAdmin/forest-rails/blob/master/LICENSE)
