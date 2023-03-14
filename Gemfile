# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.2.0"
# git_source(:github) do |repo_name|
#  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
#  "https://github.com/#{repo_name}.git"
# end

# Only required for file upload types (Guardium and Qualys to Kenna Direct), comment out if unneeded:
# gem 'nokogiri'

gem "activesupport"
gem "addressable"
gem "aws-sdk-guardduty"
gem "aws-sdk-inspector"
gem "aws-sdk-inspector2"
gem "strscan"
gem "rest-client"
gem "sanitize"
gem "tty-pager"
gem "httparty"
gem "rexml", ">= 3.2.5"
gem "ipaddress"

group :development, :test do
  gem "pry"
  gem "pry-byebug"
  gem "rspec"
  gem "rubocop", require: false
  gem "solargraph", require: false
  gem "timecop"
  gem "webmock", "~> 3.18"
  gem "vcr", "~> 6.1"
end
