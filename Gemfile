source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# failing on railway
#ruby File.read('.ruby-version')
ruby '3.2.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.8'

# Use postgresql as the database for Active Record
gem 'pg'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
gem 'redis'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# frontend build tool
gem 'vite_rails'

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# paginator for Ruby
gem 'pagy'

# Map incoming controller parameters to named scopes in the resources
gem 'has_scope'

# A fast JSON:API serializer for Ruby Objects.
gem 'jsonapi-serializer'
# provides some features to use jsonapi-serializer easier
gem 'jsonapi.rb'
gem 'ransack'

# Simple, efficient background processing for Ruby
gem 'sidekiq'

# provides support for Cross-Origin Resource Sharing (CORS)
gem 'rack-cors'

# a flexible authentication solution
gem 'devise'
# a devise extension which uses JWT tokens for user authentication
gem 'devise-jwt'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'annotate'
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails'
  gem 'pry'
  gem 'rspec-rails'

  # Linting
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'fasterer'
  gem 'license_finder', require: false
  gem 'overcommit'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console'

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem 'capybara'
  gem 'database_cleaner-active_record'
  gem 'factory_bot_rails', '< 6.4'
  gem 'faker'
  gem 'shoulda-matchers'
  # RSpec matchers for JSON API.
  gem 'jsonapi-rspec'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webdrivers'
end
