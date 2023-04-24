source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.4", ">= 7.0.4.3"

# Basic
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "bootsnap", require: false


#Auth
gem 'devise_token_auth', '~> 1.2', '>= 1.2.1'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
   gem 'listen', '~> 3.8'
   gem "spring"  
   gem 'spring-watcher-listen', '~> 2.1' 
end

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]