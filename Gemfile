source 'http://rubygems.org'
gemspec

group :development do
  case ENV['RAILS_VERSION']
  when "6"
    gem 'rails', '~> 6.1.0'
  when "7"
    gem 'rails', '~> 7.2.0'
  else
    gem 'rails', '~> 8.1.0'
  end
  # https://github.com/rails/rails/issues/6039
  gem 'activerecord-deprecated_finders', git: 'https://github.com/rails/activerecord-deprecated_finders.git'
  gem 'sqlite3', '~> 2.1'
  gem 'pry'
  gem 'test-unit'
end
