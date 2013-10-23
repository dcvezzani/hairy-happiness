source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
gem 'squeel'
gem 'pg'

gem 'comfortable_mexican_sofa', '~> 1.10.0'
gem 'comfy_blog', '~> 1.0.0'


# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'
gem 'thin'

#gem 'numbers_and_words', git: "git://github.com/kslazarev/numbers_and_words.git"
gem 'numbers_and_words'

gem "prawnto_2", :require => "prawnto"
gem 'prawn'
gem 'pdf-reader'

group :test do
  gem 'steak'
  gem 'capybara'
  gem "watchr"
end

group :production do
  gem "faker"
  gem "factory_girl_rails", ">= 3.3.0"
end

group :development, :test do
  gem 'database_cleaner'
  gem "rspec-rails", ">= 2.12.0"
  gem "faker"
  gem "factory_girl_rails", ">= 3.3.0"
  gem "shoulda"

  gem "spork", "= 1.0.0rc3"

  gem 'debugger'

  gem 'cmess', git: 'http://github.com/fac/cmess.git'
  gem 'nokogiri'
end
# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
