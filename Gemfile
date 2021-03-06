source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bootstrap
gem 'bootstrap', '~> 4.0.0.beta2.1'
# Permissions definition
gem "cancancan"
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# environment variables access
gem 'dotenv-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Use mongoDB for data storage
gem 'mongoid', '~> 6.1.0'
# Github API
gem "octokit", "~> 4.0"
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Slim template engine
gem 'slim'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Documentation generation
  gem 'yard'
end

group :test do
  # capybara
  gem 'capybara'
  # codecov
  gem 'codecov', require: false
  # ensure mongoDB is reset before test
  gem 'database_cleaner'
  # test factories
  gem "factory_bot_rails"
  # test plugin
  gem 'rails-controller-testing'
  # test runner
  gem 'rspec-rails'
  # code coverage
  gem 'simplecov', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
