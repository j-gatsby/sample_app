source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'bootstrap-sass'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'

group :development, :test do
	gem 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier'
end

gem 'jquery-rails'

group :test, :development do
	gem 'rspec-rails'
	gem 'guard-rspec'
	gem 'guard-spork'
	gem 'spork'
end

group :test do
	gem 'capybara'
	gem 'factory_girl_rails'
	gem 'cucumber-rails' 
	gem 'database_cleaner'
end

group :production do
	gem 'pg'
end
