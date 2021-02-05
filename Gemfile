source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'omniauth'
gem 'devise_token_auth'
gem 'rack-cors'
gem 'rack-attack'

gem 'friendly_id', '~> 5.1.0'

gem 'rails', '~> 5.0.7'
gem 'pg', '~> 1.2'
gem 'puma', '~> 3.12'

group :development, :test do
  gem 'rspec-rails', '~> 4.0'
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'byebug', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
