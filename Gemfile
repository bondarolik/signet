source :rubygems

gem 'addressable', '>= 2.3.1'
gem 'faraday', '~> 0.8.1'
gem 'multi_json', '>= 1.0.0'
gem 'jwt', '>= 0.1.5'
gem 'extlib', '>= 0.9.15'
gem 'jruby-openssl', :platforms => :jruby

group :development do
  # Temporary measure to avoid overly restrictive dependency on Addressable
  # introduced in Launchy 2.0.4.
  gem 'launchy', '>= 2.0.0', '<= 2.0.3'
  gem 'yard'
  gem 'redcarpet'
end

group :test, :development do
  gem 'rake', '>= 0.9.0'
  gem 'rspec', '>= 2.11.0'
  gem 'rcov', '>= 0.9.9', :platform => :mri_18
end
