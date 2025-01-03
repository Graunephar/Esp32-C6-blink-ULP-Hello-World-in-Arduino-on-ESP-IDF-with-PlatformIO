# Arduino on ESP-IDF Example for ESP32-C6

This project demonstrates how to run Arduino in an ESP-IDF project for the ESP32-C6, while also running a C program on the ULP core at the same time. If you're looking for an overview of the different ways to use Arduino and ESP-IDF on the ESP32-C6, check out my [GitHub Gist](https://gist.github.com/Graunephar/57a9882cb3a2ab98be8d63a59ab16ef3), which provides details on all my example repositories.

## **What This Project Does**

This example runs two programs in parallel:
1. **Arduino on the High Power Core (HP Core):** The Arduino program blinks the onboard RGB LED in a simple red-green-blue sequence.
2. **C Program on the Ultra-Low Power Core (ULP):** A separate C program runs on the ULP core to blink an external LED connected to GPIO3.

The purpose of this project is to show how you can leverage both cores of the ESP32-C6 for different tasks while combining the flexibility of Arduino with the advanced features of ESP-IDF.

---

## **How to Use This Project**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name