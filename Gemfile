source 'https://rubygems.org'

gem 'rails', '3.2.6'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'




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

gem "haml-rails"
gem "simple_form"
gem "decent_exposure"
gem "squeel"
group :assets do
  gem "bootstrap-sass"
end

group :development, :test do
  gem "debugger"
  gem "sqlite3"
  gem "rspec-rails"
  gem "rspec-instafail"
  gem "database_cleaner"
  gem "capybara"
  gem "capybara-webkit"
  gem "selenium-webdriver"
  gem "launchy"
  gem "factory_girl_rails"
  gem "faker"
end

group :development do
  gem "heroku"
end

group :production do
  gem "thin"
  gem "pg"
end
