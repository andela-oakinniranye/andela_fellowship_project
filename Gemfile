source 'https://rubygems.org'

gem 'sinatra', require: 'sinatra/base'
gem 'sinatra-contrib', require: 'sinatra/reloader'
gem 'datamapper'
gem 'dm-types'
gem 'slim'
gem 'bcrypt'#, require: 'bcrypt'
#gem 'sinatra-flash'#, require: 'sinatra/flash'
gem 'rack-flash3', require: 'rack-flash'
#gem 'sinatra-flash'#, require: 'sinatra/flash'
gem 'warden', require: 'warden'

group :development, :test do
  gem 'minitest'
  gem 'capybara'
  gem 'rack-test'
  gem 'dm-sqlite-adapter'
end

group :production do
  gem 'pg'
  gem 'dm-postgres-adapter'
end
