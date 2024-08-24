# ESPHome
Configuration Files for various ESPHome devices


Make sure the following lines are part of the main YAML file in ESPHome:

```yaml
packages:
  # Uncomment the appropriate package for your project
  #thewave1408.PoESP32-enviv: github://thewave1408/ESPHome/M5Stack/PoESP32-enviv.yaml@latest
  #thewave1408.PoESP32-btproxy-enviv: github://thewave1408/ESPHome/M5Stack/PoESP32-btproxy-enviv.yaml@latest
  #thewave1408.atomlite-enviv: github://thewave1408/ESPHome/M5Stack/atomlite-enviv.yaml@latest

esphome:
  name: ${name}
  friendly_name: ${friendly_name}

api:
  encryption:
    key: changeme

ota:
  - platform: esphome

```
