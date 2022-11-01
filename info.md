# BusStop Sensor

This is home assistant custom component to pull bus times from Open API.  This is pretty limited right now, simply pulling in the next three times for a given stop and route.

There is a lovelace ui custom card available here: https://github.com/wymanhns/hkbus-card

### Usage

Add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
sensor:
  - platform: busstop_sensor
    stop_name: 長宏巴士總站 #巴士站


```