source 'https://rubygems.org'
ruby '2.1.1'
#ruby-gemset=2.1.1@rails401

gem 'rails', '4.0.1'
gem 'bcrypt-ruby'
gem 'bcrypt', '~> 3.1.7'
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do 
	gem 'rspec-rails', '~> 2.0'
	gem 'rspec-activemodel-mocks'
	gem 'factory_girl_rails', "~> 4.0"
end

group :test do 
	gem 'capybara', '~> 2.1.0'
	gem 'shoulda-matchers', '~> 2.4.0' #require: false
	gem 'capybara-email', '~> 2.2.0'
end