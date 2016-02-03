source 'https://rubygems.org'

# Most current Rails version at the time of writing this
gem 'rails', '4.2.5.1'

# uses postgres as the DB: May be required to specify the path to the 'pg_config' program installed with Postgres:
#$ bundle config build.pg --with-pg-config=/Applications/Postgres.app/Contents/Versions/9.4/bin/pg_config
gem 'pg', '~> 0.15'

# SCSS for stylesheets
gem 'sass-rails', '~> 5.0'

# Compressor for JS assets
gem 'uglifier', '>= 1.3.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem "jquery-ui-rails"
gem 'json'

# Amazon AWS SDK
gem "aws-sdk"

# S3 File upload
gem 'aws-s3', :require => 'aws/s3'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry-rails'
  gem 'byebug'
  gem "factory_girl_rails"
  gem 'rspec-spec'

	# bundle exec rake doc:rails generates the API under doc/api.
	gem "sdoc", "~> 0.4.0", group: :doc
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

