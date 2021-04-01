source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.5.1"

gem "puma", "~> 5.0"
gem "rails", "~> 6.1.3"
gem "sqlite3", "~> 1.4"

gem "bootsnap", ">= 1.4.4", require: false
gem "bootstrap-sass", "~> 3.4", ">= 3.4.1"
gem "bootstrap-will_paginate", "~> 1.0"
gem "sass-rails", ">= 6"
gem "will_paginate", "~> 3.3"

gem "jbuilder", "~> 2.7"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 5.0"

gem "bcrypt", "~> 3.1", ">= 3.1.15"
gem "config", "~> 1.4"
gem "faker", "~> 2.16"
gem "figaro", "~> 1.2"

gem "active_storage_validations", "0.8.2"
gem "i18n-js"
gem "image_processing", "1.9.3"
gem "mini_magick", "4.9.5"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

group :development do
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "spring"
  gem "web-console", ">= 4.1.0"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
