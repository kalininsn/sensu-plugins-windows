## Sensu-Plugins-windows

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-windows.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-windows)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-windows.svg)](http://badge.fury.io/rb/sensu-plugins-windows)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-windows/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-windows)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-windows/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-windows)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-windows.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-windows)

## Functionality
These files provide basic Checks and Metrics for a Windows system.

## Files
 * bin/check-windows-cpu-load.rb
 * bin/check-windows-disk.rb
 * bin/check-windows-process.rb
 * bin/check-windows-ram.rb
 * bin/check-windows-service.rb
 * bin/metric-windows-cpu-load.rb
 * bin/metric-windows-disk-usage.rb
 * bin/metric-windows-network.rb
 * bin/metric-windows-ram-usage.rb
 * bin/metric-windows-uptime.rb

 * bin/powershell/check-windows-cpu-load.ps1
 * bin/powershell/check-windows-disk.ps1
 * bin/powershell/check-windows-process.ps1
 * bin/powershell/check-windows-ram.ps1
 * bin/powershell/check-windows-service.ps1
 * bin/powershell/metric-windows-cpu-load.ps1
 * bin/powershell/metric-windows-disk-usage.ps1
 * bin/powershell/metric-windows-network.ps1
 * bin/powershell/metric-windows-ram-usage.ps1
 * bin/powershell/metric-windows-uptime.ps1

## Usage
Put these files on a Sensu Client.  Typically under C:\etc\sensu\plugins.

## Installation
[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)

## Notes
