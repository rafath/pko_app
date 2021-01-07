# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

gem 'activeresource'
gem 'bootsnap', require: false
gem 'dotenv-rails'
gem 'jbuilder', '~> 2.7'
gem 'pg'
gem 'puma'
gem 'rails'
gem 'rorvswild'
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 4.0'

group :development, :test do
  gem 'brakeman'
  gem 'bullet'
  gem 'bundler-audit'
  gem 'factory_bot_rails'
  gem 'fasterer'
  gem 'ffaker'
  gem 'lol_dba'
  gem 'pry-rails'
  gem 'rails_best_practices'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'timecop'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
