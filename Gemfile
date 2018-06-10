source "https://rubygems.org"

ruby '2.5.0'

DECIDIM_VERSION = { git: "https://github.com/decidim/decidim", branch: "metadecidim" }

gem "decidim", DECIDIM_VERSION
gem "decidim-initiatives", DECIDIM_VERSION
gem "decidim-consultations", DECIDIM_VERSION

gem 'puma'
gem 'uglifier'
gem 'faker'

group :development, :test do
  gem 'byebug', platform: :mri
  gem "decidim-dev", DECIDIM_VERSION
  gem "rspec-rails"
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
