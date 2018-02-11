source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'

#slim
gem 'slim-rails'
gem 'html2slim'

#new
gem 'turbolinks'
gem 'ffi', '1.9.18'
#localegem
gem 'rails-i18n'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'

gem 'uglifier', '>= 1.3.0'
gem 'therubyracer', platforms: :ruby

gem 'bootstrap-sass'
gem 'sass-rails', '~> 5.0.6'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
end
