# Custom Ender 3 with 4-in-1-Out Mixing Hotend

## Project Overview
This project involves building a custom Ender 3 3D printer with a 4-in-1-out mixing hotend to enable multi-material and gradient extrusion capabilities. The printer integrates advanced hardware and software components to deliver precise and flexible printing performance.

---

## Hardware Components

### 1. **4-in-1-Out Mixing Hotend**
- **Model**: [4-in-1-out Mixing Hotend](https://de.aliexpress.com/item/1005005514330290.html?spm=a2g0o.order_list.order_list_main.23.664b5c5fZGz2qa&gatewayAdapt=glo2deu)
- **Features**: Allows up to four different filaments to be mixed dynamically for custom color gradients or material properties.

### 2. **Controllers**
- **Motion Controller**: Creality 4.2.2
  - Manages movement and basic functions of the printer.
- **Toolhead Controller**: SKR 1.3
  - Controls the mixing hotend and extruder motors.

### 3. **Klipper Host**
- **Device**: Pine64-LTS
  - Hosts the Klipper firmware and provides computational resources for advanced control.

---

## Firmware

### 1. **Kalico (Klipper fork)**
- **Fork**: [Kalico](https://github.com/KalicoCrew/kalico)
- **Customization**: Utilizing a personal fork of Kalico with added support for the mixing extruder. This feature will soon be merged into the main Kalico repository.
- **Why Kalico?**: Kalico extends Klipper’s capabilities, offering robust support for multi-material setups like the 4-in-1-out hotend.

---

## Features and Capabilities
- **Multi-Material Printing**: Print with up to four materials in a single job.
- **Dynamic Mixing**: Adjust filament ratios during the print for gradient effects.

---

## Future Enhancements
- **Get multi meterial Prints (meta material) to work**
- **Integration with Main Kalico Repository**: Merge the custom mixing extruder support into the official Kalico fork.
- **Extended Testing**: Optimize settings for various materials and mixing ratios.
- **Advanced Slicing Profiles**: Develop slicing configurations to fully utilize the mixing capabilities.

---

## References
- **Hotend**: [AliExpress Product Page](https://de.aliexpress.com/item/1005005514330290.html?spm=a2g0o.order_list.order_list_main.23.664b5c5fZGz2qa&gatewayAdapt=glo2deu)
- **Inspiration Video**: [CNC Kitchen](https://youtu.be/CQ-N1fr4N0w?si=kJEgdiQPMgkApnnI)
- **Kalico Fork**: [GitHub Repository](https://github.com/KalicoCrew/kalico)

