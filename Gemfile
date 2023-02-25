source "https://rubygems.org"

# A DSL for quickly creating web applications
# https://github.com/sinatra/sinatra
gem "sinatra", "~> 3.0.5"

# An object-relational mapper
# https://guides.rubyonrails.org/active_record_basics.html
gem "activerecord", "~> 7.0.4.2"

# Configures common Rake tasks for working with Active Record
# https://github.com/sinatra-activerecord/sinatra-activerecord
gem "sinatra-activerecord", "~> 2.0.26"

# Run common tasks from the command line
# https://github.com/ruby/rake
gem "rake", "~> 13.0.6"

# Provides functionality to interact with a SQLite3 database
# https://github.com/sparklemotion/sqlite3-ruby
gem "sqlite3", "~> 1.6.1"

gem "webrick", "~> 1.8.1"

# Require all files in a folder
# https://github.com/jarmo/require_all
gem "require_all"

# These gems will only be used when we are running the application locally
group :development do
  # Used to generate seed data
  # https://github.com/faker-ruby/faker
  gem "faker", "~> 3.1.1"

  # Auto-reload the server when files are changed
  # https://github.com/alexch/rerun
  gem "rerun"

  gem "pry"
end

# These gems will only be used when we are running tests
group :test do
  gem "database_cleaner"
  gem "rspec"
  gem "rack-test", "~> 1.1"
  gem "rspec-json_expectations", "~> 2.2"
end


