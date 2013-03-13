source 'http://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.12'

# Gems used only for assets and not required in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'mysql2'
end

group :production do
  gem 'pg'
  gem 'thin'
end

gem 'jquery-rails'
gem 'devise'
gem "bootstrap-sass", ">= 2.2.2.0"
gem 'carrierwave'
gem 'annotate', ">=2.5.0"
gem "bcrypt-ruby", :require => "bcrypt"