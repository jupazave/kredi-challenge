# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.6', '>= 6.1.6.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.6'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'awesome_print'
  gem 'database_cleaner-active_record'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'fuubar', '~> 2.5'
  gem 'rspec-rails'
  gem 'rubocop-performance', require: false
  gem 'rubocop-rspec', require: false
  gem 'shoulda-matchers', '~> 4.0'
  gem 'simplecov'
end

group :development do
  gem 'lefthook', '~> 1.1'
  gem 'listen', '~> 3.3'
  gem 'rubocop-rails', require: false
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'net-imap', require: false
gem 'net-pop', require: false
gem 'net-smtp', require: false

gem 'active_model_serializers', '~> 0.10.0'
gem 'active_storage_validations', '~> 0.9.8'
gem 'attr_extras', '~> 6.2'
gem 'good_job', '~> 3.4'
gem 'money-rails', '~>1.12'
gem 'ransack', '~> 3.2'
gem 'rqrcode', '~> 2.0'
gem 'will_paginate', '~> 3.3'




gem "aws-sdk-s3", "~> 1.114"
