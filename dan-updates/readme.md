# Configuring my Home Assistant from the base configuration

Original Repo here: [PeterH24x7/-Solar-Analytics-integration-for-Home-Assistant-Energy-monitoring](https://github.com/PeterH24x7/-Solar-Analytics-integration-for-Home-Assistant-Energy-monitoring)

In order to use my sensor names, some updates are required in the config file.

## Process

Rename the following references throughout the `solar_analytics.yaml` file:

- `_hot_water` -> `_spa`
- `_stove` -> `_subboard`

Create a backup copy of the existing config, then upload the config file overwriting the old one.  
Check the config is valid in developer tools.  
Restart HA.  
