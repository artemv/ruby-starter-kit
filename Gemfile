# frozen_string_literal: true

source 'https://rubygems.org'
ruby '2.6.3'

gem 'activesupport'

group :development do
  gem 'guard-bundler'
  gem 'guard-rspec', require: false
  gem 'guard-rubocop', require: false
end

group :development, :test do
  gem 'rspec'
end

group :test do
  gem 'simplecov', require: false                   # Test coverage reporting
  gem 'webmock'                                     # disallow real HTTP reqs from specs
end
