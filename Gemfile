source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.2'

gem 'rails', '~> 5.1.4'
gem 'puma', '~> 3.7'
gem 'mysql2'

gem 'dotenv-rails'
gem 'slim-rails'
gem 'sass-rails'
gem "active_model_serializers"

# JWT authorization
gem 'knock'

# omniauth
gem 'omniauth-twitter'
gem 'omniauth-github'

# API client
gem 'twitter'
gem 'octokit'

gem 'foreman'

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
