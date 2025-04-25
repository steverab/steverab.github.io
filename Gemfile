# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "webrick"

gem "jekyll", "~> 4.1"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem 'jekyll-scholar', group: :jekyll_plugins
gem "jekyll-paginate-v2", group: :jekyll_plugins

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
