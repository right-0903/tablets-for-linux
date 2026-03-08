# Tablets for Linux

I’ve been hunting for a low-cost, power-efficient, Linux-compatible
2-in-1 tablet for a long time. To be honest, it’s probably a false
need — my job has nothing to do with Linux, and I rarely travel for
work. Bringing up a new device just eats up my time, and honestly,
I think I need some new hobbies — instead of messing around with
machines. __Touch grass, man__.

This repository is a collection of tablets I’ve brought up to run Linux
(some possibly based on existing work). For now, most of them are
Qualcomm-based. Just setting up this repo as a personal log/documentation.

## Flag
*: Not working well. \
?: Untested

## Lenovo Legion Y700 Gen4
Spec.: SM8750P 16G LPDDR5X (128bit@4761MHz) + 512GB UFS 4.1 +
3040 $\times$ 1904@165Hz (native 10-bit)

Price: $\approx$ 360 USD @ 10/2028

Status: work in progress

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | x      | Sensors                     | ?      |
| Backlight                   | works  | Stylus                      | works  |
| Battery                     | works  | Suspend                     | works  |
| Bluetooth                   | x      | Thermal sensors             | x      |
| Camera                      | x      | Touchscreen over spi        | works  |
| Charge(Fast)                | works  | UFS                         | works  |
| Display(8-bit mode)         | works  | USB(2 connectors)           | works  |
| GPU                         | x      | USB-C DisplayPort Alt Mode  | x      |
| Mic                         | ?      | Video acceleration          | ?      |
| Power key & Volume key      | works  | Wi-Fi(WCN786x/WCN7880)      | x      |

### source
*To be synced*

## Lenovo Legion Y700 Gen3
Spec.: SM8650P 16G LPDDR5X (128bit@4224MHz) + 512GB UFS 4.0 +
2560 $\times$ 1600@165Hz (native 10-bit)

Price: N/A (borrowed for 2 weeks.)

Status: suspended

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | x      | Sensors                     | ?      |
| Backlight                   | works  | Stylus                      | works  |
| Battery                     | works  | Suspend                     | works  |
| Bluetooth                   | works  | Thermal sensors             | works  |
| Camera                      | x      | Touchscreen over spi        | works  |
| Charge(Fast)                | works  | UFS                         | works  |
| Display                     | ?      | USB(2 connectors)           | works* |
| GPU                         | works  | USB-C DisplayPort Alt Mode  | ?      |
| Mic                         | ?      | Video acceleration          | ?      |
| Power key & Volume key      | works  | Wi-Fi(WCN7850)              | x      |

### source
*To be synced*

## Lenovo Yoga Pad Pro 12.7 (domestic) / Lenovo Yoga Tab Plus (global)
Spec.: SM8650-AB 16G LPDDR5X (128bit@4224MHz) + 512GB UFS 4.0 +
2944 $\times$ 1840@144Hz (native 10-bit) with keyboard bundle and stylus

Price: $\approx$ 400 USD @ 08/2028

Status: suspended

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | x      | Power key & Volume key      | works  |
| Backlight                   | works  | Sensors                     | x      |
| Battery                     | works  | Stylus                      | works  |
| Bluetooth                   | works  | Suspend                     | works  |
| Camera                      | x      | Thermal sensors             | works  |
| Charge(Fast)                | works  | Touchscreen over spi        | works  |
| Display                     | x      | UFS                         | works  |
| Fingerprint reader          | x      | USB                         | works  |
| GPU                         | works  | USB-C DisplayPort Alt Mode  | x      |
| Keyboard & Touchpad         | x      | Video acceleration          | works  |
| Lid                         | x      | Wi-Fi                       | works  |
| Mic                         | x      |                             |        |

### source
*To be synced*

## Oneplus Pad Pro (domestic) / Oneplus Pad 2 (global)
Spec.: 
* SM8650-AB
* 16G LPDDR5X (128bit@3686MHz)
* 512GB UFS 4.0
* 3000 $\times$ 2120@144Hz
* with keyboard bundle and stylus

Price: $\approx$ 385 USD @ 04/2024 (+15 USD for dual EDL Authorization)

Status: Downstreamed, indefinitely suspended

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | x      | Power key & Volume key      | works  |
| Backlight                   | works  | Sensors                     | x      |
| Battery                     | works  | Stylus                      | works  |
| Bluetooth                   | works  | Suspend                     | works  |
| Camera                      | x      | Thermal sensors             | works  |
| Charge(Slow)                | works  | Touchscreen over spi        | works  |
| Display                     | works  | UFS                         | works  |
| GPU                         | works  | USB                         | works  |
| Keyboard & Touchpad         | works  | USB-C DisplayPort Alt Mode  | x      |
| Lid                         | x      | Video acceleration          | works  |
| Mic                         | works  | Wi-Fi                       | works  |

### source
*To be synced*

## Ntmer Robo & Kala TW220
Spec.:
* SC8280XP@3GHz
* 16G LPDDR4X (128bit@2092MHz)
* 512GB NVME SSD (PCIe Gen3x4)
* 2560 $\times$ 1600@60Hz
* with keyboard bundle and stylus

Price: $\approx$ 330 USD @ 02/2025

Status: Downstreamed, indefinitely suspended (I don't own the device anymore, if someone can provide the device, please contact with me)

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | works  | NVMe SSD                    | works  |
| Backlight                   | ?      | Power key & Volume key      | works  |
| Battery                     | works  | Sensors                     | ?      |
| Bluetooth                   | works  | Stylus                      | works  |
| Camera                      | x      | Suspend                     | works  |
| Charge (Fast)               | works  | Thermal sensors             | works  |
| Display                     | ?      | Touchscreen over spi        | works  |
| GPU                         | works  | USB                         | works  |
| Keyboard & Touchpad         | works  | USB-C DisplayPort Alt Mode  | x      |
| Lid                         | works  | Video acceleration          | works  |
| Mic                         | works  | Wi-Fi                       | works  |

### source
See [TW220](./TW220).

[!NOTE]
Display should work now, dsi have been supported, dispcc issues have been fixed. (*2026-03-08*)

## Huawei Matebook E Go (8cx Gen 3)
Spec.:
* SC8280XP@3GHz
* 16G LPDDR4X (128bit@2133MHz)
* 512GB NVME SSD (PCIe Gen3x4)
* 2560 $\times$ 1600@120Hz
* with keyboard bundle and stylus

Price: $\approx$ 330 USD @ 06/2024

Stats: Upstreamed

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | works  | NVMe SSD                    | works  |
| Backlight                   | works  | Power key & Volume key      | works  |
| Battery                     | works* | SLPI Sensors                | ?      |
| Bluetooth                   | works  | Stylus                      | x      |
| Camera                      | x      | Suspend                     | works  |
| Charge(Fast)                | works  | Thermal sensors             | works  |
| Display                     | works  | Touchscreen over i2c        | works* |
| EC                          | works  | Touchscreen over spi        | works* |
| Fingerprint reader          | x      | USB                         | works  |
| GPU                         | works  | USB-C DisplayPort Alt Mode  | works  |
| Keyboard & Touchpad         | works  | Video acceleration          | works  |
| Lid                         | works  | Wi-Fi                       | works  |
| Mic                         | works  |                             |        |

### source
1. [Kernel AUR](https://aur.archlinux.org/pkgbase/linux-gaokun3)
1. [Independent repo](https://github.com/right-0903/linux-gaokun)
