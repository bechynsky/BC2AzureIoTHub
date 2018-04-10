# BC2AzureIoTHub
Simple Field Gateway reading data from MQTT broker connected to BigClown USB Dongle.

# iot-hub explorer

```
iothub-explorer monitor-events BC01 --login "<connection string for service endpoint>"
```

# MQTT monitor

```
mosquitto_sub -t "#" -v
```