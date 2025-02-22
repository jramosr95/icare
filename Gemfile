# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

ruby '2.6.3'
gem 'rails', '5.2.3'

# Servers
gem 'puma', '~> 3.12'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Background jobs within the same process as web application
gem 'sucker_punch', '~> 2.1'

# Multi-environment configuration
gem 'simpleconfig', '~> 2.0'

# API
gem 'rabl', '~> 0.14.1'

# Forms
gem 'simple_form', '~> 4.1'

# ODM and related
gem 'client_side_validations', '~> 15.0'
gem 'client_side_validations-simple_form', '~> 7.0'
gem 'kaminari', '~> 1.1'
gem 'kaminari-mongoid', '~> 1.0'
gem 'mongoid', '~> 7.0'
gem 'mongoid-geospatial', '~> 5.1'
gem 'mongoid-slug', '~> 6.0'
gem 'mongoid_paranoia', '~> 0.4.0'
gem 'validates_timeliness', '~> 4.1'
gem 'validates_timeliness-mongoid', github: 'diowa/validates_timeliness-mongoid'

# Authentication framework
gem 'devise', '~> 4.6'

# Geospatial data library
# gem 'rgeo', '~> 0.6.0'

# Facebook integration
gem 'koala', '~> 3.0'
gem 'omniauth-facebook', '~> 5.0'

# Performance
gem 'newrelic_rpm', '~> 6.4'

# Security
gem 'secure_headers', '~> 6.1'

# Miscellanea
gem 'http_accept_language', '~> 2.1'
gem 'jquery-rails', '~> 4.3'
gem 'slim-rails', '~> 3.2'

# Assets
gem 'autoprefixer-rails', '~> 9.6'
gem 'coffee-rails', '~> 5.0'
gem 'handlebars_assets', '~> 0.23.4'
gem 'i18n-js', '~> 3.3'
gem 'sass-rails', '~> 5.0'
gem 'sprockets', '~> 3.7'
gem 'sprockets-rails', '~> 3.2'
gem 'turbolinks', '~> 5.2'
gem 'twbs_sass_rails', '~> 7.2'
gem 'uglifier', '~> 4.1'

group :development, :test do
  gem 'bullet', '~> 6.0'
  gem 'byebug', '~> 11.0'
  gem 'factory_bot_rails', '~> 5.0'
  gem 'faker', '~> 1.9'
  gem 'pry', '~> 0.12.2'
  gem 'pry-byebug', '~> 3.7'
  gem 'pry-rails', '~> 0.3.9'
  gem 'rspec-rails', '~> 3.8'
  gem 'rubocop', '~> 0.71.0', require: false
  gem 'rubocop-performance', '~> 1.4', require: false
  gem 'rubocop-rspec', '~> 1.33', require: false
  gem 'scss_lint', '~> 0.58.0', require: false
  gem 'slim_lint', '~> 0.17.0', require: false
end

group :development do
  gem 'better_errors', '~> 2.5'
  gem 'binding_of_caller', '~> 0.8.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring', '~> 2.1'
  gem 'spring-commands-rspec', '~> 1.0'
  gem 'spring-watcher-listen', '~> 2.0'
  gem 'web-console', '~> 3.7'
end

group :test do
  gem 'capybara', '~> 3.24'
  gem 'coveralls_reborn', '~> 0.12.0', require: false
  gem 'database_cleaner', '~> 1.7'
  gem 'email_spec', '~> 2.2'
  gem 'launchy', '~> 2.4'
  gem 'mongoid-rspec', '~> 4.0'
  gem 'poltergeist', '~> 1.18'
  gem 'selenium-webdriver', '~> 3.142'
  gem 'simplecov', '~> 0.16.1', require: false
  gem 'webmock', '~> 3.6', require: false
end

group :staging, :production do
  gem 'airbrake', '~> 9.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2018', platforms: %i[mingw mswin x64_mingw jruby]
