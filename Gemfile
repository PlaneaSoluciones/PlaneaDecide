source "https://rubygems.org"

ruby '2.4.1'

gem "decidim", "0.4.0"

gem 'puma', '~> 3.9.1'
gem 'uglifier', '>= 1.3.0'
gem 'faker', '~> 1.7.3'

group :development, :test do
  gem 'byebug', platform: :mri
  
  gem "decidim-dev", "0.4.0"
  
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.1.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'capistrano',         require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano3-puma',   require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
