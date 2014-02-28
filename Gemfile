source 'http://rubygems.org'

gem 'rails', '3.2.17'
gem 'rails-i18n', '0.6.6'
gem 'puma'
gem 'foreman', git: 'git://github.com/ddollar/foreman.git',
               tag: 'v0.45.0'

gem 'sinatra'
gem 'mysql2'
gem 'therubyracer'
gem 'haml', '~> 3.1'
gem 'haml-rails'
gem 'hpricot'
gem 'jquery-rails', '1.0.19'
gem 'simple_form', '~> 2.0'
gem "fog", "~> 1.3.1"
gem 'mini_magick'
gem 'awesome_print'
gem 'workflow', '~> 0.8.7'
gem 'high_voltage'
gem 's3_direct_upload', git: 'git@github.com:jumski/s3_direct_upload.git',
                        branch: 'on-progress-callback'
gem 'parallel'
gem 'newrelic_rpm'
gem 'tire', '~> 0.5'

gem 'sidekiq'
gem 'sidekiq-failures'
gem 'redis-objects', '~> 0.6'
gem 'clockwork'
gem 'enumerize', '~> 0.7'
gem 'json'
gem 'ruby-progressbar'
gem 'active_model_serializers', git: 'git://github.com/rails-api/active_model_serializers.git'
gem 'attribute_normalizer', '~> 1.1'
gem 'lisbn', '~> 0.1'
gem 'chunky_png', '~> 1.2'
gem 'barby', '~> 0.2'
gem 'resubject'

gem 'gon', '~> 4.0'
gem 'backbone-on-rails'
gem 'js-routes'
gem 'flutie'
gem 'bourbon'
gem 'show_for'
gem 'table_for_collection'
gem 'bootstrap-sass-rails'
gem 'google-analytics-rails'
gem 'devise'
gem 'devise-i18n'
gem 'has_scope'
gem 'kaminari'
gem 'rocket_tag', git: 'git@github.com:bradphelan/rocket_tag.git', branch: 'master'
gem 'airbrake'

gem 'alle_api', path: './vendor/alle_api'
gem 'data_migrate', '~> 1.1'
gem "highcharts-rails", "~> 3.0.0"
gem 'groupdate', '~> 1.0'
gem 'active_sanity'

group :assets do
  gem 'jquery-ui-rails', '0.4.1'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'haml_coffee_assets'
  gem 'sugar-rails'
  gem 'turbo-sprockets-rails3', '~> 0.3'
end

group :development do
  gem 'capistrano'
  gem 'capistrano_colors'
  gem 'rvm-capistrano'

  gem 'rdoc-tags'
  gem 'libnotify'
  gem 'rails-erd', '~> 1.1'
  gem 'quiet_assets'
  gem 'sql_queries_count'

  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'rails-dev-tweaks', '~> 0.6.1'
  # gem 'query_reviewer'
end

group :test, :development do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'fivemat'
  gem 'pelusa'

  gem 'interactive_editor'
  gem 'pry'
  gem 'pry-rails'
  # gem 'pry-debugger'
  gem 'pry-editline'
  gem 'konacha'
  gem 'vcr', require: false
  gem 'webmock', require: false
  gem 'launchy'
end

group :test do
  gem 'turn', require: false
  gem 'capybara'
  gem 'poltergeist', '~> 1.1'
  gem 'simplecov', require: false
  gem 'mocha'
  gem 'timecop'
  gem 'shoulda-matchers'
  gem 'sqlite3'
  gem 'mock_redis'
  gem 'site_prism', '~> 2.2', require: false
  gem 'database_cleaner', require: false
end
