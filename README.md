# Rodin-Essential Vendor Package for AOSP

This repository contains the complete, prebuilt hardware suite integration for **Xiaomi Rodin** (POCO X7 Pro / Redmi Turbo 4).

## Build Tree Integration
In your `device.mk`:
```makefile
$(call inherit-product, vendor/rodin-essential/rodin-essential.mk)
```

In your `BoardConfig.mk`:
```makefile
include vendor/rodin-essential/BoardConfigRodinEssential.mk
```
