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

## Lenovo Yoga Pad Pro 12.7 (domestic) / Lenovo Yoga Tab Plus (global)
Spec.: SM8650-AB 16G LPDDR5X (128bit@4224MHz) + 512GB UFS 4.0 +
2944 $\times$ 1840@144Hz with keyboard bundle and stylus

Price: $\approx$ 400 USD @ 08/2028

Status: work in progress

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

Status: Downstreamed, Indefinitely suspended

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
* SC8280XP@3.0GHz
* 16G LPDDR4X (128bit@2092MHz)
* 512GB NVME SSD (PCIe Gen3x4)
* 2560 $\times$ 1600@60Hz
* with keyboard bundle and stylus

Price: $\approx$ 330 USD @ 02/2025

Status: Downstreamed, Indefinitely suspended

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | works  | NVMe SSD                    | works  |
| Backlight                   | x      | Power key & Volume key      | works  |
| Battery                     | works  | Sensors                     | x      |
| Bluetooth                   | works  | Stylus                      | works  |
| Camera                      | x      | Suspend                     | works  |
| Charge (Fast)               | works  | Thermal sensors             | works  |
| Display                     | x      | Touchscreen over spi        | works  |
| GPU                         | works  | USB                         | works  |
| Keyboard & Touchpad         | works  | USB-C DisplayPort Alt Mode  | x      |
| Lid                         | works  | Video acceleration          | works  |
| Mic                         | works  | Wi-Fi                       | works  |

### source
See [TW220](./TW220).

## Huawei Matebook E Go (8cx Gen 3)
Spec.:
* SC8280XP@3.0GHz
* 16G LPDDR4X (128bit@2133MHz)
* 512GB NVME SSD (PCIe Gen3x4)
* 2560 $\times$ 1600@120Hz
* with keyboard bundle and stylus

Price: $\approx$ 330 USD @ 06/2024

Stats: Upstreamed, Indefinitely suspended

### feature matrix
| Feature                     | Status | Feature                     | Status |
|-----------------------------|--------|-----------------------------|--------|
| Audio                       | works  | NVMe SSD                    | works  |
| Backlight                   | x      | Power key & Volume key      | works  |
| Battery                     | works  | Sensors                     | x      |
| Bluetooth                   | works  | Stylus                      | x      |
| Camera                      | x      | Suspend                     | works  |
| Charge(Fast)                | works  | Thermal sensors             | works  |
| Display                     | x      | Touchscreen over i2c        | works  |
| EC                          | works  | Touchscreen over spi        | x      |
| Fingerprint reader          | x      | USB                         | works  |
| GPU                         | works  | USB-C DisplayPort Alt Mode  | works  |
| Keyboard & Touchpad         | works  | Video acceleration          | works  |
| Lid                         | works  | Wi-Fi                       | works  |
| Mic                         | works  |                             |        |

### source
1. [Kernel AUR](https://aur.archlinux.org/pkgbase/linux-gaokun3)
1. [Independent repo](https://github.com/right-0903/linux-gaokun)
