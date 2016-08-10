source 'https://rubygems.org'

# Application configuration
gem 'dotenv-rails', require: 'dotenv/rails-now', groups: [:development, :test]

gem 'rails', '~> 4.2.1'

gem 'pg'

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'slim-rails'
gem 'sprockets', '>= 3.0.0'
gem 'sprockets-es6'

gem 'jquery-rails'
gem 'quiet_assets'

source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap', '~> 3.2'
  gem 'rails-assets-bootswatch', '~> 3.3'
end
gem 'font-awesome-sass', '~> 4.4'

gem 'active_model_serializers'
gem 'responders', '~> 2.0'

gem 'devise'

gem 'draper'

gem 'redcarpet',     '~> 3.3.3'

gem 'sdoc', '~> 0.4.0', group: :doc

group :development do
  gem 'pry'
  gem 'web-console', '~> 3.0'
  gem 'rubocop'
end

group :development, :test do
  gem 'spring'
  gem 'thin'
  gem 'faker'
  gem 'guard'
  gem 'guard-minitest'
  gem 'guard-rubocop'
end

group :test do
  gem 'minitest-rails'
  gem 'minitest-rails-capybara'
  gem 'minitest-focus'
end

group :production do
  gem 'rails_12factor'
end