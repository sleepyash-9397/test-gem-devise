source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.5.1"

gem "rails", "~> 5.2.1"
gem "mysql2"
gem "puma", "~> 3.11"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "rubocop", "~> 0.54.0", require: false
gem "coffee-rails", "~> 4.2"
gem "devise"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap", "~> 4.1.3"
gem "cancancan"
gem "sprockets-rails"
gem "jquery-rails"
gem "faker"
gem "bulk_insert"
gem "bcrypt"
gem "rails-i18n"
gem "ransack", github:"activerecord-hackery/ransack"
gem "bootstrap4-kaminari-views"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "web-console", ">= 3.3.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "chromedriver-helper"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
