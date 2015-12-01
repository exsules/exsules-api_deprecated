source 'https://rubygems.org'


gem 'rails', '~> 4.2'
gem 'rails-api'
gem 'pg'

gem 'active_model_serializers', github: 'rails-api/active_model_serializers'
gem 'oj'
gem 'oj_mimic_json'

gem 'devise'

gem 'sidekiq'
gem 'sinatra', require: nil
gem 'hiredis'
gem 'redis', require: ['redis', 'redis/connection/hiredis']

gem 'figaro'

gem 'settingslogic'
gem 'colored'
gem 'seed-fu'

gem 'rack-cors', require: 'rack/cors'

gem 'puma'
gem 'pusher'

group :development do
  gem 'annotate'
  gem 'foreman', require: false
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'rerun'
  gem 'pry-rails'
  gem 'guard-rspec', require: false
end

group :development, :test do
  gem 'rspec', '~> 3.2'
  gem 'fabrication', '~> 2.13'
  gem 'mocha', require: false
  gem 'rspec-rails'
  gem 'shoulda', require: false
  gem 'rspec-given'
  gem 'spork'
  gem 'pry-nav'
  gem 'pry-byebug'
  gem 'byebug'
  gem 'web-console', '~> 2.1'
  gem 'spring'
  gem 'pusher-fake'
end


group :test do
  gem 'simplecov', require: false
end

# To use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', :group => :development

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
