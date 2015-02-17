## Sensu-Plugins-growthforecast

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-growthforecast.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-growthforecast)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-growthforecast.svg)](http://badge.fury.io/rb/sensu-plugins-growthforecast)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-growthforecast/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-growthforecast)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-growthforecast/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-growthforecast)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-growthforecast.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-growthforecast)

## Functionality

## Files
 * bin/check-current-value

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-growthforecast -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-growthforecast`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-growthforecast' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-growthforecast' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
