# 🌐 Li-Fi Technology: Wireless Communication Using Light  

A cutting-edge **Li-Fi (Light Fidelity)** project that demonstrates high-speed data transfer using light as a medium of communication. This system is built using **Arduino** and a light source, providing a simple, efficient, and eco-friendly alternative to traditional Wi-Fi for wireless communication.

---

## 🚀 Features

- 🔗 **Wireless Data Transfer**: Uses light to transmit data at high speeds.
- 💡 **Arduino Powered**: Simple implementation using Arduino boards and basic electronic components.
- 🌍 **Eco-Friendly**: A sustainable solution for wireless communication using energy-efficient light sources.
- 📊 **Speed Testing**: Demonstrates how fast data can be transferred through light.

---

## 🛠️ Technologies Used

- **Arduino**: For controlling data transfer and managing communication.
- **LED Light Source**: To send data through light waves.
- **Photoresistor (LDR)**: To receive the light signal and decode data.
- **Serial Communication**: To send and receive data between devices via light.
- **Libraries**: `Arduino IDE`, `Serial Monitor`

---

## ⚡ Workflow

1. **Light Transmission**:  
   - A message is encoded into a series of light pulses using an LED light source.
   - Arduino controls the blinking pattern of the LED to transmit the data.

2. **Light Reception**:  
   - A photoresistor (LDR) receives the light pulses.
   - Arduino decodes the received signal back into the original message using serial communication.

3. **Data Display**:  
   - The received message is displayed on a serial monitor or another output device.

---

## 📂 Folder Structure

```plaintext
Li-Fi-Technology

├── Code
│   ├── transmitter.ino      # Arduino code for data transmission (LED)
│   └── receiver.ino         # Arduino code for data reception (LDR)
│
├── Documentation
│   └── circuit_diagram.png  # Circuit diagram for connections
│
