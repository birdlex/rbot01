source 'https://rubygems.org'
# 201603
ruby '2.3.3'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# 201603
gem 'rails', '4.2.9'

#  Facebook - OLD
# gem 'devise', '~> 3.5.2'
# gem 'omniauth', '~> 1.2.2'
# gem 'omniauth-oauth2', '~> 1.3.1'
# gem 'omniauth-facebook', '~> 2.0.1'

#  Facebook - NEW
gem 'devise', '~> 4.3.0'
# 似乎是多裝的 gem 'omniauth', '~> 1.3.1'
# 似乎是多裝的 gem 'omniauth-oauth2', '~> 1.4.0'
gem 'omniauth-facebook', '~> 4.0.0'

# Sidekiq  background jobs
gem 'sidekiq', '~> 5.0.0'
gem 'sinatra', '~> 1.4.7', require: nil

#  friendly_id
gem 'friendly_id', '~> 5.2.1'

# Authorization - OLD
# gem 'cancancan', '~> 1.13'
# gem 'rolify', '~> 4.1.1'

# Authorization - NEW
gem 'cancancan', '~> 1.15'
gem 'rolify', '~> 5.1.0'

gem 'pg', '~> 0.20.0'

gem 'ckeditor', '4.2.0'

# simple configuration / settings solution that uses an ERB enabled YAML file
gem 'settingslogic', '~> 2.0.9'

# Send rails data to js
gem 'gon', '~> 6.1.0'

# Slim
gem 'slim-rails', '3.1.1'

# a Ruby library for reading and writing zip files
gem 'rubyzip', '>= 1.2.1'

# SOAP API
gem 'savon', '~> 2.11.1'

gem 'curb', '~> 0.9.3'

gem 'lograge', '~> 0.5.1'

# Image Upload
gem 'carrierwave', '~> 0.11.2'
gem 'lazyload-rails'

# currency
gem 'money-open-exchange-rates'

gem "oj", github: "ohler55/oj"
gem 'oj_mimic_json'

gem 'globalize', '~> 5.0.0'

#  Redis
gem 'redis', '~>3.3.1'
gem 'redis-rails'

group :development, :staging, :production do
  gem 'koala', '~> 2.4.0'
  # tool to profile memory usage
  # gem 'rbtrace'

  # MetaSearch
  gem 'ransack', '~> 1.8.2'

  # INSPINIA admin theme
  gem 'bootstrap-sass', '~> 3.3.7'
  # 201605
  gem 'font-awesome-rails', '4.6.3.1'
  gem 'coffee-rails', '~> 4.2.1'
  gem 'sass-rails', '~> 5.0.6'

  gem 'uglifier', '>= 3.0.2'
  gem 'turbolinks', '~> 2.5.3'
  gem 'jbuilder', '~> 2.6.0'

  # Cache
  # 201605
  gem 'dalli', '~> 2.7.6'
  gem 'connection_pool', '~> 2.2.1'

  # Pagination
  gem 'kaminari', '~> 0.17.0'
  gem 'kaminari-bootstrap', '~> 3.0.1'

  # SMS
  # 201603
  gem 'twilio-ruby', '~> 4.13.0'

  # jQuery
  gem 'jquery-rails', '~> 4.2.1'
  gem 'jquery-validation-rails', '~> 1.13.1'

  gem 'mini_magick', '~> 4.5.1'

  # i18n
  gem 'rails-i18n', '~> 4.0.0'
  gem 'devise-i18n', '~> 1.1.0'

  # Bootstrap generators for Rails
  gem 'bootstrap-generators', '~> 3.3.4'

  gem 'bootstrap-datepicker-rails', '~> 1.6.4.1'

  # web server
  # 201605
  gem 'puma', '~> 3.9.1'

  gem 'nested_form', '~> 0.3.2'

  # validate, display and save phone numbers
  gem 'phony_rails', '~> 0.14.6'

  # Cron jobs in Ruby
  # 201605
  gem 'whenever', '~> 0.9.7', require: false

  # generates barcodes in a variety of symbologies
  # 201605
  gem 'barby', '~> 0.6.4'

  gem 'cairo', '~> 1.15.2'

  # read and write PNG files
  gem 'chunky_png', '~> 1.3.7'

  gem 'html5shiv-js-rails', '~> 3.7.3.1'
  # implements read access for all common spreadsheet types
  # It can handle:
  # Excel 2007 - 2013 formats (xlsx, xlsm)
  # LibreOffice / OpenOffice.org formats (ods)
  # CSV
  # Excel 97, Excel 2002 XML, and Excel 2003 XML formats when using the roo-xls gem (xls, xml)
  # Google spreadsheets with read/write access when using roo-google
  gem 'roo', '~> 2.5.1'
  # 201605
  gem 'respond-js-rails', '~> 1.4.2.2'

  # Google Cloud Platform for Carrierwave
  gem "fog-google", '~> 0.5.3'
  gem "google-api-client", "< 0.9"

  # a library and registry for information about MIME content type definitions
  gem 'mime-types', '~> 3.1', require: 'mime/types/full'
  # FPTS Connection
  gem 'double-bag-ftps', github: 'wconrad/double-bag-ftps', branch: 'ruby-2.3'
  # Dropzone is an easy to use drag'n'drop library
  gem 'dropzonejs-rails'
  gem 'intl-tel-input-rails'
end

group :development, :test do
  gem 'pry'
end

group :doc do
  gem 'sdoc', '~> 0.4.1', require: false
end

group :production do
  # 201605
  gem 'newrelic_rpm'
  gem 'rollbar'
end

group :development do
  # gem 'better_errors', '~> 2.1.1'
  # gem 'binding_of_caller', '~> 0.7.2'

  # page load performance analytic tool, must below `gem 'pg'`
  # gem 'rack-mini-profiler'

  # another performance analytic tool
  # Type ?pp=flamegraph to create one for the current page.
  # gem 'flamegraph'

  # notify you when you should add eager loading (N+1 queries),
  # when you're using eager loading that isn't necessary and
  # when you should use counter cache.
  # gem 'bullet'

  # code style checker
  # 201605
  gem 'rubocop', '~> 0.44.1'
  # 201605
  gem 'capistrano', '~> 3.9.0'
  gem 'capistrano-postgresql', '~> 4.2.1'
  gem 'capistrano-rails', '~> 1.3.0'
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'capistrano-sidekiq', github: 'seuros/capistrano-sidekiq'
  gem 'capistrano3-puma', github: 'seuros/capistrano-puma'
  gem 'spring', '~> 1.7.2'
  gem 'web-console'
end

group :test do
  # 201605
  gem "ci_reporter", '~> 2.0.0'
  gem 'ci_reporter_rspec', '~> 1.0.0'
  gem 'factory_girl', '~> 4.7.0'
  gem 'factory_girl_rails', '~> 4.7.0'
  gem 'faker', '~> 1.6.6'
  gem 'rspec-rails', '~> 3.6.0'
  gem 'shoulda-matchers', '~> 3.1.1'
  # rspec with jenkins
  gem "simplecov", '~> 0.12.0'
  gem "simplecov-rcov", '~> 0.2.3'
end
gem 'nokogiri', '>= 1.8.1'

