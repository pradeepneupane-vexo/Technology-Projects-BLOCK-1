# Part 4 – Raspberry Pi Hardware Identification
Upload:
```
images/raspberry-pi/pi-board.jpg
images/raspberry-pi/labelled-pi-board.jpg
```
---

| Component | Function |
|-----------|----------|
| SoC | |
| GPIO | |
| USB | |
| HDMI | |
| Power | |
| microSD | |
| Network | |
| Wireless | |

---
## Reflection
Why are many components integrated into a single board in embedded computers such as the Raspberry Pi?
Write **100 words**.

---

## Answers

| Component | Function |
|---|---|
| SoC | System on a chip containing the CPU, graphics processing, and other controllers; exact integration depends on the model. |
| GPIO | General purpose input/output pins for digital signals and supported interfaces such as I2C, SPI, and UART. |
| USB | Connects peripherals such as keyboards, mice, and external storage. |
| HDMI | Sends digital video and audio to a monitor or television; connector type varies by model. |
| Power | Accepts the electrical supply needed to operate the board; connector and requirements depend on the model. |
| microSD | Typically stores the operating system, applications, and files and provides a boot medium on models with a slot. |
| Network | Wired Ethernet connectivity on equipped models. |
| Wireless | Wi-Fi networking and Bluetooth connectivity on equipped models. |

### Reflection answer (100 words)

Integrating components onto one board reduces the space, wiring, and assembly work needed to build an embedded computer. Short connections help signals travel reliably, while shared power circuitry simplifies supplying the system. Integration can also reduce manufacturing costs and make a design easier to reproduce. A Raspberry Pi combines processing and interfaces in a compact platform that can control sensors, communicate over networks, and run software. This suits projects with limited space, such as monitoring devices or robots. However, integration creates tradeoffs: individual components are harder to replace or upgrade, and cooling and available connections can limit what projects require.

**Practical evidence pending:** Identify the actual Raspberry Pi model and add the original and labelled board photographs. Component locations and available interfaces must match that model.
