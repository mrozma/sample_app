source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', '1.3.6', :group => :development

group :development do
  gem 'rspec-rails', '>=2.2.0'
  gem 'webrat', '0.7.1'
  gem 'pg'
end

group :test do
  gem 'rspec-rails', '>=2.2.0'
  gem 'webrat', '0.7.1'
  gem 'spork'
end

group :production do
  gem 'pg'
end

#this is a must for Heroku deployment, Chris 2012/9/21
group :production do
  #gem 'therubyracer-heroku', '0.8.1.pre3' # you will need this too
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
