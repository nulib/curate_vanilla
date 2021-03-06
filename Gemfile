source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use sqlite3 as the database for Active Record
gem 'mysql2'

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
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'therubyracer', group: [:development, :staging]

gem "curate", github: 'projecthydra/curate', ref: '195d2173ef66c6740dbcad0d9933d2167a5e0e46'
gem "better_errors", group: :development
gem "binding_of_caller", group: :development
gem "quiet_assets", group: :development
gem "bootstrap-sass"
gem "devise"
gem "devise-guests", "~> 0.3"
group :development, :test do
  gem "rspec-rails"
  gem "byebug"
end

gem "jettywrapper", group: [:development, :test]

group :deploy do
  gem 'capistrano', '~> 2.15'
end

group :staging do
  gem "sentry-raven"
end

group :headless do
  gem 'clamav'
end
