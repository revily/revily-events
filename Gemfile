source 'https://rubygems.org'

gem 'rails',                                '4.0.0'

gem 'active_model_serializers',             github: 'rails-api/active_model_serializers'
gem 'metriks',                              '0.9.9.5'
gem 'dalli',                                '2.6.4'
gem 'request_store'

group :development do
  gem 'guard-rspec',                        require: false
  gem 'guard-spork',                        require: false
  gem 'guard-shell',                        require: false
  gem 'libnotify',                          require: false
  gem 'method_profiler',                    require: false
  gem 'perftools.rb',                       require: false
  gem 'pry-rails'
  gem 'rblineprof',                         require: false
  gem 'rbtrace',                            require: false
  gem 'rb-fsevent',                         require: false
  gem 'rb-inotify',                         require: false
  gem 'ruby-graphviz',                      require: false
  gem 'ruby-prof',                          require: false
  gem 'ruby_gntp',                          require: false
  gem 'spork-rails',                        require: false, github: 'sporkrb/spork-rails'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'json_spec'
  gem 'rspec-rails'
  gem 'shoulda-matchers',                   require: false
  gem 'timecop'
  gem 'webmock'
  gem 'vcr'
end
group :development, :test do
  gem 'awesome_print'
  gem 'factory_girl_rails'
  gem 'forgery'
  gem 'sham_rack'
end

group :staging, :production do
  gem 'airbrake'
  gem 'newrelic_rpm'
end

group :doc do
  gem 'redcarpet'
  gem 'yard'
end
