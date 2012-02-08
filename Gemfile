source 'http://rubygems.org'

gem 'rails', '3.1.1'


platforms :jruby do
  gem 'jruby-openssl'
  gem 'jrclj', :git => "git://github.com/kyleburton/jrclj.git", :branch => "cc0a0be630eb01f64680811edc48270b5fe77dcb"
  gem 'activerecord-jdbcsqlite3-adapter'
end

platforms :ruby do
  gem 'sqlite3'
end

gem 'jquery-rails'
gem "bson_ext", "~> 1.4"
gem "mongoid", "~> 2.4"
gem "devise", ">= 1.4.9"

gem 'airbrake'
gem 'cancan'
gem 'mongoid_session_store'
gem 'switch_user'
gem 'pusher'
gem 'kaminari'
gem 'rails-backbone'
gem 'newrelic_rpm'
gem 'momentjs-rails'

gem 'twitter-bootstrap-rails', :git => "git://github.com/seyhunak/twitter-bootstrap-rails.git", :branch => "static"
gem 'twitter_bootstrap_form_for'

gem 'haml-rails'
gem "trinidad"
gem "trinidad_logging_extension"



# In test, no mail gets sent anyway, but let's not mess with the email addresses
gem 'mail_safe', :groups => [ :development, :staging ]

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'haml_coffee_assets'

  # The less version requires v8, which doesn't work with JRuby. See
  # http://rubysource.com/twitter-bootstrap-less-and-sass-understanding-your-options-for-rails-3-1/
  # for deciding the correct option.
end



group :test do
  gem "rspec-rails", ">= 2.7.0"
  gem "cucumber-rails", ">= 1.1.1"
  gem "capybara", ">= 1.1.1"
  gem "sauce"
  gem "database_cleaner", ">= 0.6.7"
  gem "mongoid-rspec", ">= 1.4.4"
  gem "factory_girl_rails", ">= 1.3.0"
  gem "launchy", ">= 2.0.5"
  gem "minitest"
  gem 'turn', :require => false  # Pretty printed test output
  gem 'flexmock'
  gem 'rspec-html-matchers'
  gem 'jasmine'
end


group :development do
  gem 'rake'
  gem 'hpricot'
  gem 'ruby_parser'
  gem 'jasmine'
end



# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
