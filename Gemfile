source 'https://rubygems.org'
ruby '2.3.3'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
#gem 'rails', '4.1.1'
gem 'rails', '~> 5.2.4', '>= 5.2.4.3'

# Use postgresql as the database for Active Record
gem 'pg', '~> 0.19.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'execjs'
gem 'therubyracer', platforms: :ruby

gem 'active_model_serializers', '~> 0.10.3'

# Http request
gem 'httparty', require: false

gem 'graphql'
gem 'graphql-activerecord', '>= 0.12.3'
gem 'graphql-batch'
gem 'graphiql-rails', '>= 1.4.2'

# Elasticsearch
gem 'elasticsearch'
gem 'elasticsearch-model', '>= 0.1.9'
gem 'elasticsearch-rails'

# Paging the results
gem 'kaminari', '>= 0.17.0'

gem 'oj'
gem 'oj_mimic_json'

# This is to run the rake task for importing in parallel
gem 'parallel'
# Will provide a progress bar as the import happens

gem 'prose'

gem 'puma', '~> 3.0'

gem 'redis-rails', '>= 5.0.1'

gem 'rack-cors'

gem 'sentry-raven'

gem 'sitemap_generator'

gem 'virtus'

gem 'tzinfo-data'

# Detect the language
gem 'whatlanguage'

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'zeus'
end

group :test do
  gem 'rspec-rails' , '>= 3.5.2' # http://betterspecs.org/
  gem 'guard-rspec', require: false
  gem 'parallel_tests'
  gem 'simplecov', :require => false
end

group :development do
  gem 'annotate', '>= 2.7.1'
  gem 'ruby-progressbar'
  gem 'byebug', platform: :mri
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '>= 2.0.0'
  gem 'spring-commands-rspec', '>= 1.0.4'
  gem 'spring-watcher-listen', '~> 2.0.1'
  gem 'mechanize'
  gem 'bullet', '>= 5.5.0'
  gem 'meta_request', '>= 0.5.0'
  gem 'rubocop', require: false
end
