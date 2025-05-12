# frozen_string_literal: true

source "https://rubygems.org"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end

# gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins
# gem "jekyll-scholar", group: :jekyll_plugins
gem "webrick", "~> 1.8.1", group: :jekyll_plugins

gemspec
gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?
gem 'jekyll-paginate'
gem 'public_suffix', '~> 5.0.3'
gem 'addressable', '~>  2.8.5'
gem 'diff-lcs', '~> 1.5.0'
gem 'ffi', '~> 1.16.3'
gem 'google-protobuf', '~> 3.24.4'
gem 'sass-embedded', '~> 1.69.3'
gem 'jekyll-sass-converter'
gem 'kramdown' #, '~> 2.3.2'
gem 'mercenary', '~> 0.3.3'
gem 'rouge'
gem 'unicode-display_width', '~> 2.5.0'
gem 'terminal-table', '~> 3.0.2'
# gem 'webrick', '~> 1.8.1'
# gem 'jekyll', '~> 3.9.3'
# gem 'jekyll', '~> 4.3.2'
gem 'nokogiri', '~> 1.15.4'
gem 'rack', '~> 2.2.8'
gem 'rspec-support', '~> 3.12.1'
gem 'rspec-core', '~> 3.12.2'
gem 'rspec-expectations', '~> 3.12.3'
gem 'rspec-mocks', '~> 3.12.6'
gem 'rspec', '~> 3.12.0'
# gem 'jekyll-scholar'

# Last version
gem "jekyll", "~> 4.3.3"          # Latest stable Jekyll 4.x
gem "jekyll-scholar", "~> 7.0"     # Requires Jekyll 4+
gem "bibtex-ruby", "~> 6.0"        # Newer version (optional)


# gem "rails"

gem "rake", "13.0.6"  # Match the version in the error