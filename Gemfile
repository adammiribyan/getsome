source 'https://rubygems.org'

gem 'rails', '3.2.0'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'uglifier', '>= 1.0.3'
end

# Simple forms
gem 'simple_form'

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Capybara for integration tests
  gem 'capybara'
  gem 'database_cleaner'
  # Girls in a factories
  gem 'factory_girl_rails'
  # Spork
  gem 'spork', '~> 0.9.0.rc'
  gem 'spork-testunit'
  gem 'ruby-prof' # for benchmarks
  # Guards
  gem 'guard-spork'
  gem 'guard-test', "~> 0.4.3"
end

group :production do
  gem 'therubyracer'
end
