source "https://rubygems.org"
gem "jekyll", "~> 4.0.0"
gem "minima", "~> 2.5"

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end
gem "wdm", :install_if => Gem.win_platform?