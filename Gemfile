ruby '3.2.2'
source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '7.0.6'
gem 'pg', '1.5.3'
gem 'puma', '6.3.0'
gem 'jbuilder', '2.11.5'
gem 'redis', '5.0.6'
gem 'bcrypt', '3.1.19'
gem 'bootsnap', '1.16.0'
gem 'image_processing', '1.12.2'
gem 'sprockets-rails', '3.4.2'

gem 'simple_form', '5.2.0'
gem 'haml-rails', '2.1.0'
gem 'redcarpet', '3.6.0'

gem 'omniauth-google-oauth2', '1.1.1'
gem 'omniauth-rails_csrf_protection', '1.0.1'
gem 'httparty', '0.21.0'
gem 'sucker_punch', '3.1.0'
gem 'graphql-client', '0.18.0'
gem 'zammad_api', '1.1.0'
gem 'nokogiri', '1.15.3'

gem 'kaminari', '1.2.2'

gem 'pg_search', '2.3.6'

gem 'ransack', '4.0.0'

# Use Tailwind CSS framework
gem "tailwindcss-rails", "2.0.30"

# Bundle JavaScript
gem "jsbundling-rails", "1.1.2"

# Push data to Geckoboard
gem 'geckoboard-ruby', '0.4.0'

# Build reusable UI components
gem 'view_component', '3.5.0'

# Talk with Productive API
gem 'productive', '0.6.70'

# Present data with charts
gem "chartkick", "5.0.3"
gem "groupdate", "6.3.0"

# Collect performance information and catch errors
gem "appsignal", "3.4.9"

group :development, :test do
  gem 'byebug', '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '3.39.2'
  gem 'cuprite', '0.14.3'
  gem 'webmock', '3.18.1'
  gem 'vcr', '6.2.0'
end

group :development do
  gem 'listen', '3.8.0'
  gem 'better_errors', '2.10.1'
  gem 'binding_of_caller', '1.0.0'
  gem 'letter_opener', '1.8.1'
end

group :test do
  gem 'simplecov', '0.22.0'
  gem 'simplecov_json_formatter', '0.1.4'
  gem 'factory_bot', '6.2.1'
  gem 'faker', '3.2.0'
end
