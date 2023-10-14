source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails",           "7.1.1"
gem "sassc-rails",     "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "importmap-rails", "1.2.1"
gem "turbo-rails",     "1.5.0"
gem "stimulus-rails",  "1.3.0"
gem "jbuilder",        "2.11.5"
gem "puma",            "6.4.0"
gem "bootsnap",        "1.16.0", require: false
gem "sqlite3",         "1.6.7"

group :development, :test do
  gem "debug", "1.8.0", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console", "4.2.1"
  gem "solargraph",  "0.49.0"
end

group :test do
  gem "capybara",                 "3.39.2"
  gem "selenium-webdriver",       "4.14.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest",                 "5.20.0"
  gem "minitest-reporters",       "1.6.1"
  gem "guard",                    "2.18.1"
  gem "guard-minitest",           "2.4.6"
end

# Windows ではタイムゾーン情報用の tzinfo-data gem を含める必要があります
gem "tzinfo-data", platforms: %i[ windows jruby ]