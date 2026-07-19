# 🚗 BSRP Speedometer

A modern and lightweight speedometer system built exclusively for the **BSRP Framework**.

BSRP Speedometer provides a clean, responsive, and optimized vehicle HUD experience designed to integrate seamlessly with the BSRP ecosystem. Built with performance and customization in mind, it delivers essential vehicle information while maintaining smooth gameplay performance.

---
📸 Preview <img width="258" height="205" alt="image" src="https://github.com/user-attachments/assets/1276a35a-0f66-4a65-a72e-9d70e3639018" />


## 📌 Features

✅ Fully integrated with **BSRP Framework**
✅ Modern vehicle HUD design
✅ Real-time speed display
✅ Vehicle information tracking
✅ Optimized performance
✅ Lightweight resource usage
✅ Easy configuration
✅ Designed for future BSRP expansions

---

## 🔗 Requirements

This resource requires:

* **BSRP Framework**

  * Repository: https://github.com/BSRPFreeRoam/BSRP-FrameWork

* FiveM Server

* GTA V

* OneSync Recommended

---

## 📥 Installation

### 1. Download

Download or clone the resource into your server resources folder:

```bash
cd resources
git clone https://github.com/BSRPFreeRoam/BSRP-Speedometer.git
```

---

### 2. Add to `server.cfg`

Add the following:

```cfg
ensure BSRP-Speedometer
```

Make sure the **BSRP Framework** starts before this resource:

```cfg
ensure BSRP-FrameWork
ensure BSRP-Speedometer
```

---

## ⚙️ Configuration

All settings can be found inside:

```
config.lua
```

Example:

```lua
Config = {}

Config.SpeedUnit = "MPH"

Config.ShowFuel = true

Config.ShowEngineHealth = true

Config.ShowVehicleInfo = true
```

---

## 🎨 Customization

You can customize:

* HUD position
* Colors
* Speed units
* Vehicle information
* Display options
* UI appearance

Modify the configuration files to match your server's branding.

---

## 🖥️ Framework Integration

BSRP Speedometer is designed specifically for:

* BSRP Framework
* BSRP Vehicle Systems
* Future BSRP resources

The resource communicates directly with the BSRP ecosystem to provide a smooth and consistent experience.
