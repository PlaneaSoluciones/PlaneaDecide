source "https://rubygems.org"

ruby '2.4.1'

gem "decidim", git:"https://github.com/decidim/decidim"
gem "decidim-module-blogs", git:"https://github.com/decidim/decidim-module-blogs"
gem 'puma'
gem 'uglifier'
gem 'faker', "1.8.4"

group :development, :test do
  gem 'byebug', platform: :mri
  
  gem "decidim-dev", git:"https://github.com/decidim/decidim"
  
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
