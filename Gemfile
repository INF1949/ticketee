source 'http://rubygems.org'

gem 'rails', '3.1.0'
#Required to cause cucumber-rails to load the files in the book
#  BUT ITS NO LONGER AVAILABLE!
# gem 'cucumber-rails' '1.0.6'
# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem "dynamic_form"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

#We're not going to use Test::Unit
#group :test do
  # Pretty printed test output
#  gem 'turn', :require => false
#end

group :test, :development do
	gem 'rspec-rails', '~>2.5'
end
group :test do	
	gem 'cucumber-rails'
	gem 'capybara'
	gem 'database_cleaner'
	gem "factory_girl", '1.3.3'
	gem 'email_spec'
end
gem 'devise', '~> 1.4.3'
