source 'https://rubygems.org'

gemspec

gem 'rake'

group :development do
  gem 'ruby_gntp'
  gem 'guard-rspec'
end

# The test group will be
# installed on Travis CI
#
group :test do
  gem 'rspec'
  gem 'fakefs'
  gem 'coveralls', require: false
end

gem 'therubyrhino', platforms: :jruby
gem 'therubyracer', platforms: :ruby
