source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.2'

# #1
group :production do
  # Use pg as the production database for Active Record
  gem 'pg'
  gem 'rails_12factor'
end

# #2
group :development do
  # Use sqlite3 as the development database for Active Record
  gem 'sqlite3'
end

group :development, :test do
  gem 'rails-controller-testing'
  gem 'rspec-rails', '~> 3.0'
end
# for markdown syntax
gem 'redcarpet', '~> 3.3', '>= 3.3.4'
# for payments
gem 'stripe', '~> 3.4', '>= 3.4.1'
# lets the DB be rest w/ Docker
gem 'pgreset', '~> 0.1.1'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# use faker to gen seeds for users & wikis
gem 'faker', '~> 1.6', '>= 1.6.6'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

gem 'thor', '0.19.1'

gem 'bootstrap-sass'

gem 'rubocop', '~> 0.52.1', require: false

gem 'devise', '~> 4.3'
# Pundit for authorization
gem 'pundit'
gem 'simple_form', '~> 3.2', '>= 3.2.1'
group :development do
  gem 'listen', '~> 3.0.5'
end
