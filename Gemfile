source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.1"

gem "rails", "~> 6.0.3", ">= 6.0.3.2"

gem "bootsnap", ">= 1.4.2", require: false
gem "puma", "~> 4.1"
gem "rack-cors"

gem "bcrypt", "~> 3.1.7"
# gem "image_processing", "~> 1.2"
gem "interactor"
gem "jwt"
gem "pg", ">= 0.18", "< 2.0"

gem "decent_exposure", "~> 3.0.0"
gem "jbuilder", "~> 2.7"

group :development, :test do
  gem "brakeman", require: false
  gem "bullet"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem "rspec-rails"
  gem "rubocop", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
end

group :test do
  gem "database_cleaner-active_record"
  gem "guard-rspec"
  gem "launchy"
  gem "rspec-its"
  gem "shoulda-matchers"
end

group :development do
  gem "letter_opener"
  gem "listen", "~> 3.2"
  gem "rails-erd"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end
