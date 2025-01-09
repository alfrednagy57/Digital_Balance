# Digital Weighing Device

This project implements a digital weighing device designed to measure weights, calculate prices, and provide an interactive user experience. It combines embedded systems, electronics, and software to create a functional solution for retail environments.

---

## Features

1. **Weight Measurement**: Reads weight data using an HX711 load cell.
2. **Product Selection**:
   - Allows users to choose from various vegetables and fruits via a keypad.
   - Displays selected items and their prices on an LCD.
3. **Price Calculation**:
   - Calculates the price based on the selected product and weight.
   - Maintains a running total of prices.
4. **Order Management**:
   - Add or remove items from the current order.
   - View the updated total price dynamically.
5. **Final Output**: Displays the final total price of the order on the LCD.
6. **Troubleshooting**:
   - Recalibration of the load cell.
   - Diagnostics for keypad and LCD.

---

## Project Overview

### Components
- **Microcontroller**: Manages overall operations.
- **Load Cell (HX711)**: Measures weight accurately.
- **Keypad**: User interface for product selection and interaction.
- **LCD Display**: Provides feedback, displays weight, prices, and total cost.
- **Power Supply**: Stable and reliable performance.

### Software
- Embedded C code for core functionality.
- EEPROM for load cell calibration values.
- HX711 library for weight measurement.

---

## Circuit Design

The device is composed of:
1. A microcontroller connected to the load cell via the HX711 ADC.
2. A 4x4 keypad for user input.
3. An LCD display for real-time feedback.
4. Power supply circuit for stable operation.

---

## Usage

### How It Works:
1. **Startup**:
   - Power on the device.
   - The LCD will display a welcome message.
2. **Product Selection**:
   - Choose a category (vegetables/fruits) and a specific product.
3. **Weighing**:
   - Place the item on the scale to measure its weight.
4. **Price Calculation**:
   - The system calculates the price based on the weight and product price.
5. **Order Management**:
   - Add or remove items from the cart.
6. **Final Total**:
   - Confirm the total price and finalize the order.

---

## Online simulation : 
   **LINK :** https://wokwi.com/projects/418369321627150337

---

## Simulation Photos
![PXL_20240712_200756368](https://github.com/alfrednagy57/user-attachments/blob/main/IMAGES_/Screenshot%202025-01-01%20030313.png?raw=true)
![PXL_20240712_200813083](https://github.com/alfrednagy57/user-attachments/blob/main/IMAGES_/Screenshot%202025-01-01%20030318.png?raw=true)
![PXL_20240712_200813083](https://github.com/alfrednagy57/user-attachments/blob/main/IMAGES_/Screenshot%202025-01-01%20030258.png?raw=true)
![PXL_20240712_200813083](https://github.com/alfrednagy57/user-attachments/blob/main/IMAGES_/Screenshot%202025-01-01%20030328.png?raw=true)
![PXL_20240712_200813083](https://github.com/alfrednagy57/user-attachments/blob/main/IMAGES_/Screenshot%202025-01-01%20030302.png?raw=true)

## Requirements

### Hardware
- STM32 Nucleo Board (e.g., Nucleo32F446RE) or any Arduino boards.
    - programmed using arduino IDE.
- HX711 Load Cell.
- LCD (16x2).
- 4x4 Keypad.
- Power Supply.

### Software
- Arduino IDE.
   - and intall these libraries (Keypad.h,LiquidCrystal.h,HX711.h,EEPROM.h).    
- HX711 and Keypad libraries.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/alfrednagy57/Digital_Balance.git
   cd Digital_Balance

---

## Contact

For any inquiries, please contact the project maintainer at [linkedin](https://www.linkedin.com/in/alfred-nagy-882445224/).
