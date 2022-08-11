source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "kramdown-parser-gfm"
gem "webrick", "~> 1.7"

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
