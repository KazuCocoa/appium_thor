require File.expand_path '../lib/appium_thor', __FILE__

Appium::Thor::Config.set do
  appium_thor = 'appium_thor'
  gem_name     appium_thor
  github_name  appium_thor
  github_owner 'appium'
  version_file "lib/#{appium_thor}/version.rb"
  docs_block do
    run 'docs/helpers_docs.md', globs("/lib/#{appium_thor}/helpers.rb")
  end
end