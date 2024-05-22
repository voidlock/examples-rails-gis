source 'https://rubygems.org'

ruby '3.3.1'

gem 'geocoder'
gem 'jquery-rails'
gem 'newrelic_rpm'
gem 'puma'
gem 'rails', '~> 7.1.3.2'

group :assets do
  gem 'sprockets-rails', :require => 'sprockets/railtie'
  gem 'uglifier', '>= 4.2.0'
end

# for POW
group :development do
  gem 'sqlite3', '~> 2.0', '>= 2.0.1'
end

# for Heroku, even though we never use the DB.
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# ==========
# MemCachier
# ==========
# We recommend kgio for better performance.
gem 'dalli'
gem 'kgio'
gem 'memcachier'
