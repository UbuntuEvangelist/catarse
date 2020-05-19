source 'https://rubygems.org'

ruby '2.2.3'

gem 'rails', '~> 5.2.4', '>= 5.2.4.3'

gem 'protected_attributes'
gem 'rails-observers', '>= 0.1.4'
gem 'rb-readline'

gem 'sidekiq',  '~> 4.0.1'

# Turns every field on a editable one
gem "best_in_place", :git => "git://github.com/bernat/best_in_place", ref: "ee95961e639022e6aa528704b8cb4789596ea61b"

# State machine for attributes on models
gem 'state_machine', require: 'state_machine/core'
gem 'statesman'

# Database and data related
gem 'pg', '0.17.1'
gem 'dbhero', '>= 1.1.9'
gem 'postgres-copy', '>= 1.0.0'
gem 'pg_search', '>= 1.0.5'
gem 'i18n_alchemy', '>= 0.3.0'
gem "i18n-js", ">= 3.0.0.rc11"

gem 'schema_plus'
gem 'catarse_settings_db', '>= 0.1.1'

# Notifications
gem 'user_notifier', '~> 0.3.1'

# Mixpanel for backend tracking
gem 'mixpanel-ruby'
gem 'mixpanel_client'

# Payment engines
gem 'catarse_pagarme', '~> 2.8.8'
#gem 'catarse_pagarme', path: '../catarse_pagarme'

# Decorators
gem 'draper', '>= 2.1.0'

# Frontend stuff
gem 'slim-rails', '>= 3.1.0'
gem 'browser'
gem "cocoon"

# Static pages
gem 'high_voltage'

# Authentication and Authorization
gem 'simple_token_authentication', '~> 1.14', '>= 1.14.0' # see semver.org
gem 'omniauth'
gem 'omniauth-facebook'
gem 'koala'
gem 'devise', '>= 4.4.2'
gem 'pundit', '>= 1.0.1'
gem 'json_web_token'

# Email marketing
gem 'catarse_monkeymail', '>= 0.1.6'
gem 'gridhook', '>= 0.2.0'

# HTML manipulation and formatting
gem 'simple_form', '>= 4.0.0'
gem 'mail_form', '>= 1.7.1'
gem "auto_html"
gem 'kaminari', '>= 0.16.3'
gem 'redactor-rails', github: 'catarse/redactor-rails'

# Uploads
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave', ref: '1578777fe3f30140347ebf27d1943471bbe4d425'
gem "mini_magick"

# Other Tools
gem 'to_xls'
gem 'ranked-model', '>= 0.4.0'
gem 'feedjira'
gem 'inherited_resources', '>= 1.9.0'
gem 'has_scope', '>= 0.7.2'
gem 'spectator-validates_email', '>= 0.2.0', require: 'validates_email'
gem 'video_info', '~> 2.4.2'
gem 'typhoeus'

# Translations
gem 'http_accept_language'
gem 'routing-filter', '~> 0.6.2.0'

group :production do
  # Gem used to handle image uploading
  gem 'fog-aws'

  # Workers, forks and all that jazz
  gem 'unicorn'

  # Enabling Gzip on Heroku
  # If you don't use Heroku, please comment the line below.
  gem 'heroku-deflater', '>= 0.4.1'

  # Make heroku serve static assets and loggin with stdout
  #gem 'rails_on_heroku'
  gem 'rails_12factor'

  # Monitoring with the new new relic
  gem 'newrelic_rpm'

  # Using dalli and memcachier have not presented significative performance gains
  # Probably this is due to our pattern of cache usage
  # + the lack of concurrent procs in our deploy
  #gem 'memcachier'
  #gem 'dalli'
end
group :development do
  gem 'rack-mini-profiler'
  gem "rails-erd", ">= 1.4.4"
  gem "letter_opener"
  gem 'foreman'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'thin'
  # Uncomment only for optimization, should be commented on master branch
  # gem 'rack-mini-profiler'
  # gem 'ruby-prof'
end

group :test, :development do
  gem 'rspec-rails', '~> 3.5', '>= 3.5.0'
  gem 'rspec-mocks'
  gem 'rspec-its'
  gem 'rspec-collection_matchers'
  gem 'pry'
  gem 'jasmine-rails', '>= 0.12.2'
end

group :test do
  gem 'zonebie'
  gem 'fakeweb'
  gem 'poltergeist'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'shoulda', '>= 3.5.0'
  gem 'factory_girl_rails', '>= 4.5.0'
  gem 'capybara',   '~> 2.2.0'
  gem 'selenium-webdriver'
end

gem 'sass-rails', '>= 5.0.5'
gem 'coffee-rails', '>= 4.2.2'
gem 'compass-rails', '>= 2.0.5'
gem 'uglifier'
gem 'sprockets'
