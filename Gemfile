source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'rails', '6.1.4.4'

# Basic
gem 'bootsnap', '~> 1.9', require: false
gem 'pg', '< 2.0'
gem 'puma', '~> 5.5'

# Auth
gem 'devise_token_auth', '~> 1.1.4'

# Rendering
# gem 'jbuilder', '~> 2.7'

# Cors + Security
gem 'rack-cors', '~> 1.1.1'
# gem 'rack-attack', '~> 6.6.0'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'rspec-rails', '~> 5.0.0'
  gem 'shoulda-matchers', '~> 5.1.0'
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
