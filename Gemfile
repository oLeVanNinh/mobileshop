source 'https://rubygems.org'

git_source(:github) do |repo_name|
 repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
 "https://github.com/#{repo_name}.git"
end

 gem "rails", "~> 5.1.4"
 gem "figaro"

 gem "puma", "~> 3.7"
 gem "pg", "~> 0.18"
 gem "bootstrap-sass", "~> 3.3.7"
 gem "sass-rails", "~> 5.0"
 gem "uglifier", ">= 1.3.0"
 gem "coffee-rails", "~> 4.2"
 gem "turbolinks", "~> 5"
 gem "jbuilder", "~> 2.5"
 gem "font-awesome-rails"
 gem "devise"
 gem "config"
 gem "ckeditor"
 gem "jquery-rails"
 gem "ransack"
 gem "faker"
 gem "bootstrap-will_paginate", "1.0.0"
 gem "carrierwave"
 gem "cocoon"
 gem "toastr-rails"
 gem "hirb"
 gem "momentjs-rails"
 gem "rails_bootstrap_sortable"
 gem "mysql2", "~> 0.3.18"

group :development, :test do
 gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
 gem "capybara", "~> 2.13"
 gem "factory_bot_rails"
 gem "better_errors"
 gem "guard-rspec", require: false
 gem "database_cleaner"
 gem "brakeman", require: false
 gem "jshint"
 gem "bundler-audit"
 gem "rubocop", "~> 0.51.0", require: false
 gem "rubocop-checkstyle_formatter", require: false
 gem "eslint-rails", git: "https://github.com/octoberstorm/eslint-rails", require: false
 gem "scss_lint_reporter_checkstyle", require: false
 gem "rails_best_practices"
 gem "reek"
 gem "railroady"
 gem "autoprefixer-rails"
 gem "jquery-turbolinks"
 gem "will_paginate"
 gem "bcrypt"
end

group :development do
 gem "web-console", ">= 3.3.0"
 gem "listen", ">= 3.0.5", "< 3.2"
 gem "spring"
 gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
 gem "simplecov", require: false
 gem "simplecov-rcov", require: false
 gem "simplecov-json"
 gem "shoulda-matchers"
end

group :production do
  gem "rails_12factor", "0.0.2"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
