# Edit this Gemfile to bundle your application's dependencies.
source 'http://gemcutter.org'

gem "rails", "3.2"
gem "sqlite3-ruby", :require => "sqlite3"
gem 'jquery-rails'
gem "execjs"
gem "therubyracer"
gem 'will_paginate', '~> 3.0' # version added for rails 3 compatibility
gem "nokogiri"
gem "paperclip"
gem "client_side_validations"
gem "whenever"
gem "plist"
gem "cancan"
gem "highline"
gem "newrelic_rpm"
gem "highcharts-rails", "~> 2.1.9"
gem "dynamic_form" # enabling this should allow the removal of vendor/dynamic_form

group :development do
  # gem "ruby-debug19" , :require => "ruby-debug"
  gem "rails-erd"
  gem "textmate_backtracer"
end

group :test, :development do
  gem "pry-rails"
  gem "rspec-rails", "~> 2.6"
  gem "capybara"
  gem "launchy"
  gem "guard-rspec"
  gem "guard-cucumber"
end

group :test do
  gem 'cucumber-rails'
  gem "factory_girl_rails"
  gem 'database_cleaner'
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end