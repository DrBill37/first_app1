source 'https://rubygems.org'

gem 'rails', '3.2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'sqlite3'

# which forces Bundler to install version 1.3.5 of the sqlite3 gem. Note that we�ve
# also taken this opportunity to arrange for SQLite to be included only in a development
# environment (Section 7.1.1), which prevents potential conflicts with the database used by Heroku

group :development do
    gem 'sqlite3', '1.3.5'
end


#gem 'therubyracer'


# Gems used only for assets and not required
# in production environments by default.
#group :assets do
#  gem 'sass-rails',   '~> 3.2.3'
#  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

#  gem 'uglifier', '>= 1.0.3'
#end

group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.2.3'
end

gem 'jquery-rails'
####gem 'jquery-rails', '2.0.0'  #the bundler could not find this version as requested by the guide example

group :production do
  gem 'pg', '0.12.2'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
