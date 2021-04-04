# telegraf-snmp-mikrotik

This repo contains Telegraf SNMP plugin configuration for Router OS (mikrotik) devices as I couldn't find any good configuration online.

## Usage

The configuration files contain only relevant parts, you probably want to *add* it to your current telegraf configuration.

The configuration was tested only with handful of mikrotik models like:
 - 2011UiAS-2HnD
 - 750GL
 - CCR1009-8G-1S-1S+
 - RB760iGS (Mikrotik hEX S)

Not all features are supported.

## TODO

Create multiple model-specific versions, where only supported metrics are collected.

## Contributing

Contributions are welcome, please create a pull request.
