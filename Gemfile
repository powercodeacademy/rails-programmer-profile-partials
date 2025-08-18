
source 'https://rubygems.org'

ruby '3.3.5'

# Core Rails 7.1
gem 'rails', '~> 7.1.0'
gem 'puma', '~> 6.0'
gem 'sqlite3', '~> 1.6'
gem 'sassc-rails'
gem 'jbuilder', '~> 2.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'jquery-rails'
gem 'ostruct'

# Asset pipeline (Sprockets is optional in Rails 7, but included for legacy asset support)
gem 'sprockets-rails'

group :development, :test do
  gem 'byebug'
  gem 'spring'
  gem 'rspec-rails', '~> 6.0'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'simplecov', require: false
  gem 'database_cleaner-active_record'
  gem 'pry'
  gem 'guard-rspec', require: false
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

# Documentation
gem 'sdoc', '~> 0.4.0', group: :doc

# Remove deprecated gems: uglifier, coffee-rails, bootstrap-sass, rails_12factor
# If you need Bootstrap, use the modern webpacker or importmap approach for Rails 7+
