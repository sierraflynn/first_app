source 'http://rubygems.org'

ruby '1.9.2'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# added from 1.4.2 to make errors go away and commented out 2nd line
# gem install sqlite3 -v '1.3.8'
group :development do
   gem 'sqlite3' #, '1.3.8'
end
# gem 'sqlite3'

# added from section 1.4.1:
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end
