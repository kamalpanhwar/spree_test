source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

gem 'rails', '~> 6.1.1'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.4', require: false

gem 'spree', '~> 4.2'
gem 'spree_auth_devise', '~> 4.3'
gem 'spree_gateway', '~> 3.9'
gem 'spree_i18n', '~> 5.0'
gem 'sassc', github: 'sass/sassc-ruby', branch: 'master' # only needed for MacOS and Ruby 3.0
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "figaro", "~> 1.2"

gem "capistrano", "~> 3.16"
gem "capistrano-bundler", "~> 2.0"
gem "capistrano-passenger", "~> 0.2.1"
gem "capistrano-rails", "~> 1.6"
gem "capistrano-figaro-yml", "~> 1.0"

gem "capistrano-rbenv", "~> 2.2"
