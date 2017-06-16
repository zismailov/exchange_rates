source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "pg", "~> 0.18"
gem "puma", "~> 3.7"
gem "rails", "~> 5.1.1"
gem "sass-rails", "~> 5.0"
gem "therubyracer", platforms: :ruby
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "factory_girl_rails"
  gem "faker"
  gem "pry"
  gem "rspec-rails"
end

group :development do
  gem "guard"
  gem "guard-bundler"
  gem "guard-rspec"
  gem "rubocop"
  gem "seedbank"
end

group :test do
  gem "database_cleaner"
  gem "shoulda-matchers"
end
