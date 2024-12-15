# Configuring my Home Assistant from the base configuration

Original Repo here: [PeterH24x7/-Solar-Analytics-integration-for-Home-Assistant-Energy-monitoring](https://github.com/PeterH24x7/-Solar-Analytics-integration-for-Home-Assistant-Energy-monitoring)

In order to use my sensor names, some updates are required in the config file.

## Process

Rename the following references throughout the `solar_analytics.yaml` file:

- `_hot_water` -> `_spa`
- `_stove` -> `_subboard`
- `Hot Water Energy` -> `Spa Energy`
- `Stove Oven Energy` -> `Sub Board Energy`
- `subboard_oven` -> `subboard`
- `icon_template: mdi:shower-head` -> `icon_template: mdi:hot-tub`
- `icon_template: mdi:stove` -> `icon_template: mdi:power-socket-au`

Create a backup copy of the existing config, then upload the config file overwriting the old one.  
Check the config is valid in developer tools.  
Restart HA.  
