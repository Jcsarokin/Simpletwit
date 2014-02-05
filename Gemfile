source 'https://rubygems.org'

gem 'rails', '4.0.2'
gem 'bootstrap-sass', '~> 2.0.0'

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails', '2.10.0'
	gem 'guard-rspec', '~> 0.5.5'
end

group :assets do
	gem 'sass-rails', '~> 4.0.0'
	gem 'uglifier', '>= 1.3.0'
	gem 'coffee-rails', '~> 4.0.0'

end

gem 'jquery-rails'

group :production do
	gem 'pg', '~> 0.12.2'
end

gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Test gems on Macintosh OS X
group :test do
  gem 'capybara', '~> 1.1.2'
  gem 'growl', '1.0.3'
  gem 'spork-rails'
  gem 'guard-spork'
end
