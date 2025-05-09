# MQTT Topic Tree for ESPHome - Piano4 / Studio

This document outlines all MQTT topics published by the ESPHome node `sensore_piano4_studio`, located in the area `Piano4`, stanza `Studio`.

## 📡 MQTT Topics

```
Piano4/Studio/
├── Ambiente/
│   ├── Pressione
│   ├── Temperatura
│   └── Umidita
├── Aria/
│   ├── CO2
│   ├── Temperatura
│   └── Umidita
├── Diagnostica/
│   ├── Bluetooth
│   ├── Engineering Mode
│   ├── ESP_Reboot
│   ├── Esp temperatura
│   ├── IP
│   ├── DNS
│   ├── MAC
│   ├── Query
│   ├── Reboot
│   ├── Reset
│   ├── Uptime
│   └── Versione
├── IR/
│   └── Accendi_TV
├── Luce/
│   └── Lux
├── Presenza/
│   ├── Detection distance
│   ├── Light
│   ├── Move energy
│   ├── Moving distance
│   ├── Moving_target
│   ├── Out_pin
│   ├── Presence
│   ├── Still energy
│   ├── Still distance
│   ├── Still_target
│   ├── G0/
│   │   ├── Move_Energy
│   │   ├── Still_Energy
│   │   ├── Move Threshold
│   │   └── Still Threshold
│   ├── G1/ ... G8/
│   │   (identico a G0 per ogni gruppo)
│   └── Parametri/
│       ├── Baud Rate
│       ├── Distance Resolution
│       ├── G0 → G8/
│       │   ├── Move Threshold
│       │   └── Still Threshold
│       ├── Light Function
│       ├── Light Threshold
│       ├── Max Move Distance
│       ├── Max Still Distance
│       ├── Out Pin Level
│       └── Timeout
```