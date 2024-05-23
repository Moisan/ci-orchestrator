# frozen_string_literal: true

source "https://rubygems.org"

ruby file: ".ruby-version"

gem "faraday-retry" # for octokit
gem "jwt"
gem "octokit"
gem "orka_api_client", git: "https://github.com/Homebrew/orka_api_client"
gem "puma"
gem "rackup"
gem "sinatra"

group :development, optional: true do
  gem "rubocop"
  gem "rubocop-performance"
end
