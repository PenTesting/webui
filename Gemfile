source 'https://rubygems.org'
gem 'rails', '5.2.8.1'
gem 'sqlite3'

gem 'rdiscount'

group :assets do
    gem 'sass-rails', '~> 5.0.5'
    gem 'coffee-rails', '~> 4.2.2'
    gem 'uglifier', '>= 2.7.2'
end

gem 'factory_girl', group: [:test]
gem 'jquery-rails', '4.4.0'
gem "thin"
#gem "rspec-rails", ">= 2.11.0", group: [:development, :test]
gem "capybara", ">= 2.0.2", group: :test
gem "cucumber-rails", ">= 1.3.0", group: :test, require: false
gem "database_cleaner", ">= 0.8.0", group: :test
gem "launchy", ">= 2.1.0", group: :test
gem "machinist", group: :test
gem "bootstrap-sass", ">= 3.4.0"
gem "simple_form", ">= 5.0.0"
gem "devise", ">= 4.7.1"
gem "cancan", ">= 1.6.8"
gem "rolify", ">= 3.1.0"

gem 'libv8', '~> 3.11.8'
gem "therubyracer", group: :assets, platform: :ruby

gem "rails-settings-cached"

gem 'rails-footnotes', '>= 3.7.7', group: :development
gem 'kaminari', '>= 1.2.1'

gem 'arachni-rpc-em', git: 'git://github.com/Arachni/arachni-rpc-em.git'

if File.exist?( p = File.dirname( __FILE__ ) + '/../arachni' )
    gem 'arachni', git: "#{p}/.git", branch: 'no-webui'
else
    gem 'arachni', github: 'Arachni/arachni', branch: 'no-webui'
end
