source ENV['GEM_SOURCE'] || "https://rubygems.org"

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 3.2']
end

gem 'rake'
gem 'puppet-lint'
gem 'rspec-puppet'
gem 'puppet', puppetversion
