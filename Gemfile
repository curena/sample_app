source 'https://rubygems.org'

gem 'rails', '3.2.12'
gem 'pg', '0.12.2' #postgres

group :development, :test do
  gem 'rspec-rails', '2.11.0' #Rspec is an automated testing tool.
  gem 'guard-rspec', '1.2.1' #Guard runs tests automatically based on changes to your files.
  gem 'guard-spork', '1.2.0' #Guard-spork allows you to run Guard along with Spork.
  gem 'spork', '0.9.2' #Spork is used to speed up the test-running process by pre-loading your Rails environment.
  gem 'childprocess', '0.3.6' #using earlier version to work around known issue with Guard with Spork. 
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-fsevent', '0.9.1', :require => false
  gem 'growl', '1.0.3'
end