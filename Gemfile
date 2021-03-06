source 'https://rubygems.org'
ruby '2.4.2'

gem 'rails', '5.1.4'

gem 'jquery-rails'
gem 'pg'
gem 'omniauth', '~> 1.7.1'
gem 'omniauth-github'
gem 'omniauth-twitter'
gem 'octokit'
gem 'rabl'
gem 'kaminari', '~> 1.1.0'
gem 'twitter'
gem 'bootstrap-sass'
gem 'jquery-datetimepicker-rails'
gem 'simple_form'
gem 'coffee-rails'
gem 'uglifier'
gem 'octicons_helper'
gem 'rack-canonical-host'
gem 'draper', '~> 3.0.1'
gem 'responders'
gem 'gmaps4rails'
gem 'geocoder', '~> 1.4.5'
gem 'lodash-rails'
gem 'typhoeus'
gem 'sassc-rails'
gem 'puma'
gem 'rack-attack'

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'rubocop', require: false
  gem 'web-console'
  gem 'figaro'
  gem 'meta_request'
end

group :development, :test, :cucumber do
  gem 'i18n-tasks'
  gem 'rspec-rails'
  gem 'simplecov', require: false
  gem 'codeclimate-test-reporter', require: false
  gem 'rails-controller-testing'

  gem 'rspec-its', require: false
  gem 'rspec-collection_matchers', require: false
  gem 'rspec-activemodel-mocks', require: false
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'brakeman'
  gem 'poltergeist'
  gem 'launchy'

  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'webmock', '~> 3.1.0', require: false
  gem 'timecop'
  gem 'christmas_tree_formatter'
end

group :production do
  gem 'foreman'
  gem 'dalli'
  gem 'rails_12factor'
  gem 'newrelic_rpm'
  gem 'bugsnag'
  gem 'rack-google-analytics'
end
