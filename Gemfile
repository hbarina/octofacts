source "https://rubygems.org"

gemspec name: "octofacts"
gemspec name: "octofacts-updater"

group :development do
  gem "parallel", "= 1.12.0"
  gem "pry", "~> 0.10"
  gem "rake", "~> 10.0"
  gem "rubocop-github", "~> 0.5.0"
  gem "simplecov", ">= 0.14.1"
  gem "simplecov-json", "~> 0.2"

  # Integration test
  gem "rspec-puppet", "~> #{ENV['RSPEC_PUPPET_VERSION'] || '2.6.2'}"
  gem "puppet", "~> #{ENV['PUPPET_VERSION'] || '4.10.4'}"
end
