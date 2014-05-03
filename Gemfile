source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'

# Bootstrap CSS framework added to project
gem 'bootstrap-sass', '~> 3.1.1'

# Seperating development and production for use in Heroku
group :development do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

#Seed data using FAKER for testing
gem 'faker'

#Using devise for user Signin
gem 'devise'

#Simple file uploads to S3 | This may change as we decide which storage systems to implement for users
gem 'carrierwave'

#Twitter API interface
gem 'twitter'

#Will be needed later when converting data for use in mobile apps
gem 'json'

#Catches exception with Airbrake gem | will list errors in Airbrake Server for review
gem 'airbrake'

#Allows access to facebook graph via Graph | Facebook Connect and OAuth authentication
gem 'koala'

#The Omniauth which combines sign in options
gem 'omniauth'

#Facebook signin
gem 'omniauth-facebook', '1.4.0'

#allows Google sign in | Needed if we choose to use google drive for storage
gem 'omniauth-google-oauth2'

#Allows for Twitter registration and sign in
gem 'omniauth-twitter'

#Using mini magick over RMagick to keep files small
gem 'mini_magick'

#Simple form for flexible and simple form use
gem 'simple_form'

#waiting to decide if to implement thin as a development server 
#gem 'thin'



# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
