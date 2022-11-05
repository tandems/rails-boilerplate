source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

ruby '3.1.2'

gem 'rails', '~> 7.0.3'

gem 'active_hash'
gem 'active_interaction', '~> 5.2'
gem 'sprockets-rails'
gem 'anyway_config', '~> 2.0'
gem 'bootsnap', require: false
gem 'dotenv-rails'
gem 'enumerize'
gem 'faker'
gem 'gimei'
gem 'mysql2', '~> 0.5'
gem 'puma', '~> 5.0'
gem 'rack-cors'
gem 'seed-fu', '~> 2.3'
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]

group :development, :test do
  gem 'awesome_print'
  gem 'debug', platforms: %i[ mri mingw x64_mingw ]
  gem 'factory_bot_rails'

  # pry
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
end

group :production, :staging do
  gem 'aws-healthcheck'
end

group :development do
  gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'letter_opener_web'
  gem 'rack-mini-profiler'
  gem 'rails-erd'
  gem 'web-console'

  # static code analysis
  gem 'brakeman'
  gem 'rails_best_practices'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
end

group :test do
  gem 'factory_bot_rails'
  gem 'fuubar'
  gem 'json-schema_builder'
  gem 'rspec-rails'
  gem 'rswag-specs'
  gem 'timecop'
end
