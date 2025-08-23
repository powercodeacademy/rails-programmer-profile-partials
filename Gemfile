# Ensure Ruby 3.x compatibility for JSON parsing
gem 'json', '>= 2.0'

source 'https://rubygems.org'

ruby '3.3.5'

# Core Rails 7.1
gem 'bootsnap', '>= 1.4.4', require: false
gem 'jbuilder', '~> 2.0'
gem 'jquery-rails'
gem 'ostruct'
gem 'puma', '~> 6.0'
gem 'rails', '~> 7.1.0'
gem 'sassc-rails'
gem 'sqlite3', '~> 1.6'

# Asset pipeline (Sprockets is optional in Rails 7, but included for legacy asset support)
gem 'sprockets-rails'

group :development, :test do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'byebug'
  gem 'capybara'
  gem 'database_cleaner-active_record'
  gem 'guard-rspec', require: false
  gem 'pry'
  gem 'rspec-rails', '~> 6.0'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'spring'
  gem 'webrick'
end

group :development do
  gem 'listen', '~> 3.7'
end

group :test do
  gem 'webmock'
end

group :production do
  gem 'google-analytics-rails'
end

# Remove deprecated gems: uglifier, coffee-rails, bootstrap-sass, rails_12factor
# If you need Bootstrap, use the modern webpacker or importmap approach for Rails 7+
