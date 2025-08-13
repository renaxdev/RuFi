# RuFi – Dinner’s ready, minus the yelling

**RuFi** is a simple one-button call device to notify someone instantly — no shouting required.  
Perfect for letting family members know when dinner is ready or when you need assistance.

---

## 📖 Inspiration
My parents used to call me or my sister for dinner, but we often didn’t hear them (or pretended not to 🙃).  
RuFi replaces shouting with a simple button in Home Assistant that sends a signal directly to the person you want to reach.

---

## ⚙️ Features
- **One-button operation** – instant notification.
- **ESP32-C6 Supermini** – the brain of the device.
- **Active buzzer + LED** – loud and visible alerts you can’t miss.
- **LiPo battery powered** – portable and wireless.
- **Wi-Fi antenna** – about +6 dBm extended range.
- **Configurable with ESPHome** – simple `.yaml` file for easy customization.

---

## 🛠 Hardware
- **Microcontroller:** ESP32-C6 Supermini
- **Power:** Small LiPo battery
- **Alert system:** Active buzzer + LED
- **Antenna:** External (optional)
- **Enclosure:** Hive-style design (STL files in repo)
- **PCB:** Prototyping board (no custom PCB)

---

## 🖥 Software
RuFi is configured with [ESPHome](https://esphome.io/), making it easy to integrate into Home Assistant.

The YAML configuration file included in this repo defines:
- Button input
- Buzzer and LED control
- Wi-Fi setup
- Signal sending logic

---

## 📐 Enclosure
The hive-style enclosure was designed in **Fusion360**.  
You can find the STL files in the `hardware/case` folder of this repository.

---

## 🚀 Getting Started
1. **Flash** the ESP32-C6 with the included ESPHome YAML file (do not forget to change your WiFi credentials!).
2. **Assemble** the hardware (wiring diagram in `hardware`).
3. **Add** the device to Home Assistant.
4. **Press the button** and enjoy silent (but loud and blinky) notifications.

---

## 📷 Gallery
![RuFi Device](https://mkoerner.dev/rufi.png)

---

## 🔗 Related Links
- [ESPHome Documentation](https://esphome.io/)
