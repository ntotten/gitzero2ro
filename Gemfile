source 'https://rubygems.org'

gem "rack", "~> 1.5.2"
gem "rake"

gem 'unicorn'
gem 'dotenv-rails', :groups => [:development, :test]

gem "coveralls", :require => false

group :test do
  gem "test"
  gem "rack-test", "~> 0.6.2"
  gem "mocha"
  gem "simplecov", :require => false # Disable for ruby 1.8
  #gem "rcov", :require => false # Enable for ruby 1.8
end
