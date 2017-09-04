source "https://rubygems.org"

ruby '2.4.1'

gem "decidim", "0.5.1"
gem "decidim-accountability", git: "https://github.com/decidim/decidim-accountability.git"

gem 'puma'
gem 'uglifier'
gem 'faker', "1.8.4"

group :development, :test do
  gem 'byebug', platform: :mri
  
  gem "decidim-dev", "0.5.1"
  
end

group :development do
  gem 'letter_opener'
  gem 'letter_opener_web'
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'capistrano',         require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano3-puma',   require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
