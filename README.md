# telegraf-snmp-mikrotik
This repo contains Telegraf snmp plugin configuration for Router OS (mikrotik) devices as I couldn't find any good configuration online.

## Usage

The telegraf.conf file contains only relevant part, you probably want to *add* it to your current telegraf configuration.

The configuration was tested only with handful of mikrotik models like:
 - 2011UiAS-2HnD
 - 750GL

Not all features are supported.

## TODO

Create multiple model-specific versions, where only supported metrics are collected.

## Contributing

Contributions are wellcome, please create pull request.
