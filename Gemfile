ruby "1.9.3"

source :rubygems

gem 'sinatra'
gem 'activesupport', '~> 2.3', :require => 'active_support'
gem 'yajl-ruby', :require => [ 'yajl', 'yajl/json_gem' ]
gem 'faraday'


gem 'hoptoad_notifier'
gem "sentry-raven"

# service: mail
gem 'mail', '~> 2.2'

# service :campfire
gem 'tinder', '~> 1.4'

# service :hipchat
gem 'hipchat-api'

# service :libratometrics
gem 'librato-metrics', '~> 1.0.1', :require => "librato/metrics"

group :development do
  gem 'foreman'
  gem 'heroku'
end

group :building do
  gem 'rake'
end

group :production do
  gem 'pg'

  # Use unicorn as the web server
  gem 'unicorn'
  
  gem 'puma'
end

group :test do
  gem 'mocha', :require => false
end
