source 'https://rubygems.org'

gem 'rails', '~> 4.2.5.2'
gem 'mysql2'

gem 'jquery-rails'

gem 'activeresource'

gem 'figaro'
gem 'puma'
gem 'bugsnag'
gem 'bcrypt'
# The latest master branch has major performance improvements for GraphQL parsing
gem 'graphql', github: 'rmosolgo/graphql-ruby', ref: '2546a37b2bd4c0e0163943b9a09eec3fec39d78e'
gem 'graphql-relay'
gem 'graphiql-rails', github: 'rmosolgo/graphiql-rails'
gem 'browserify-rails'
gem 'hashie'
gem 'devise', '~> 3.5.4'
gem 'devise_invitable'
gem 'acts_as_paranoid', github: 'ActsAsParanoid/acts_as_paranoid', tag: 'v0.5.0.beta2'
gem 'nokogiri', '~> 1.6.7.2'
gem 'statsd-instrument', '~> 2.0.0'
gem 'will_paginate', '~> 3.0.6'
gem 'sidekiq'
gem 'sinatra', require: false
gem 'sinatra-contrib', require: false
gem 'httparty'
gem 'twine-rails'
gem 'turbograft'
gem 'redis-rails'
gem 'measured'

# File uploading
gem 'carrierwave'
gem 'fog', require: 'fog/aws'
gem 'mini_magick'

group :test do
  gem 'awesome_print'
  gem 'brakeman'
  gem 'webmock', require: false
end

group :development do
  gem 'web-console', '~> 3.0'
  gem 'letter_opener_web', '~> 1.2.0'
  gem 'quiet_assets'
  gem 'foreman'
end

group :development, :test do
  gem 'byebug'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-theme'
  gem 'pry-stack_explorer'
  gem 'spring'
  gem 'spring-commands-testunit'
  gem 'guard'
  gem 'guard-minitest'
  gem 'partially_useful'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'mocha', require: false
  gem 'faker'
end
