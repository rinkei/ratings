ruby '2.1.4'

source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
group :development do
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano3-unicorn'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Use bootstrap
gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem "twitter-bootstrap-rails", github: "seyhunak/twitter-bootstrap-rails", branch: "bootstrap3"

# Use Slim as the templating engine
gem 'slim-rails'

# Use Simple Form
gem 'simple_form', '~> 3.1.rc1'

# Use FactoryGirl
gem 'factory_girl_rails'

# Use rails-i18n
gem 'i18n_generators', group: :development

# Use ransack for search
gem 'ransack'

# Use devise for users' authentication
gem 'devise'

group :development, :test do
  # Use RSpec
  gem 'rspec-rails', '~> 3.0.0.beta'

  # Use pry for debug
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  # gem 'pry-stack_explorer' # not work on rails4
  gem 'hirb'
  gem 'hirb-unicode'
  gem 'tapp'
  gem 'awesome_print'

  # Hide assets' log
  gem 'quiet_assets'

  # Use Turnip
  gem 'turnip'
  gem 'capybara'
  gem 'poltergeist'
end

