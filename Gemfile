source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'
#gem 'sqlite3'

# Added pagination and mini-profiler
gem 'kaminari'
gem 'rack-mini-profiler'

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
gem 'faker'

group :development, :test do
  gem 'rspec-rails'
  gem 'pry-rails'
  gem 'pry-doc'
# pry-debugger broken in ruby 2.1.0 TODO add it back in when debugger works again (usually by 2.1.x>0)
#  gem 'pry-debugger'
  gem 'hirb'
end

group :test do
  gem 'test-unit'
  gem 'ruby-prof'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

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
