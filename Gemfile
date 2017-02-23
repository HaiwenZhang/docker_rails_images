if ENV['USE_OFFICIAL_GEM_SOURCE']
  source 'https://rubygems.org'
else
  source 'https://gems.ruby-china.org'
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0', '>= 5.0.1'

# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 4.2', '>= 4.2.1'

gem 'sass-rails', '~> 5.0', '>= 5.0.6'

# Use mysql as the database for Active Record
gem 'mysql2', '~> 0.4.5'

# Use Puma as the app server
gem 'puma', '~> 3.6', '>= 3.6.2'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
#
gem 'connection_pool', '~> 2.2', '>= 2.2.1'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 3.3', '>= 3.3.2'
gem 'redis-namespace', '~> 1.5', '>= 1.5.2'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors', '~> 0.4.0'

# User system
gem 'devise', '~> 4.2.0'
gem 'devise-encryptable', '~> 0.2.0'

# API
gem 'active_model_serializers', '~> 0.10.4'

# json web token ruby
gem 'jwt', '~> 1.5', '>= 1.5.6'

# Read dotenv environment variables
gem 'dotenv-rails', '~> 2.1.1'

# Authorization
gem 'pundit', '~> 1.1.0'

# Paginator
gem 'kaminari', '~> 0.17.0'

# Ruby library for reading and writing zip file
gem 'rubyzip', '~> 1.2.0'

# spreadsheet handling tool
gem 'roo', '~> 2.5'

# Background processing
gem 'sidekiq', '~> 4.2.7'

# Zero MQ driver
gem 'ffi-rzmq', '~> 2.0', '>= 2.0.4'
# Http
gem 'faraday', '~> 0.10.1'

# JSON Library
gem 'multi_json', '~> 1.11', '>= 1.11.2'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'pry', '~> 0.10.4'

# Use mina for deployment AWS server
group :production do
  gem 'mina', '~> 0.3.8'
  gem 'mina-puma', '~> 0.3.1', require: false
  gem 'mina-sidekiq', '~> 0.4.1', require: false
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 9.0.6', platform: :mri
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  gem 'factory_girl_rails', '~> 4.7.0'
  gem 'database_cleaner', '~> 1.5.3'

  # Annotate models
  gem 'annotate', '~> 2.7.1'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '~> 3.4.0'
  gem 'listen', '~> 3.0.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0.0'
  gem 'spring-watcher-listen', '~> 2.0.1'
  # Better Errors
  gem 'better_errors', '~> 2.1.1'
  # A Ruby code quality reporter
  gem "rubycritic", '~> 3.1.1', :require => false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2.2', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
