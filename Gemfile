# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.7.1'

gem 'rails', '~> 7.0.0.alpha'

gem 'ar_lazy_preload', git: 'https://github.com/omohokcoj/ar_lazy_preload'
gem 'audited'
gem 'devise', git: 'https://github.com/strobilomyces/devise', branch: 'patch-1'
gem 'dotenv'
gem 'fast_blank'
gem 'image_processing'
gem 'lograge'
gem 'motor-admin'
gem 'mysql2', require: false
gem 'oj'
gem 'pg', require: false
gem 'puma'
gem 'sqlite3'
gem 'webpacker'

group :development, :test do
  gem 'brakeman', require: false
  gem 'byebug'
  gem 'letter_opener'
  gem 'pry-rails'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'yard', require: false
end

group :development do
  gem 'listen'
  gem 'spring'
  gem 'web-console'
end
