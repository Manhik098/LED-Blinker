# 555 Timer LED Blinker Circuit

This project is a simple LED blinking circuit using the 555 Timer IC in **Astable Mode**. The output from the timer is used to drive three LEDs via a BC547 NPN transistor.

## 🧠 Features

- Utilizes 555 Timer in Astable mode.
- Adjustable blinking frequency using a 100kΩ potentiometer.
- Controls multiple LEDs with a single transistor switch.
- Powered by a 5V DC supply.

## ⚙️ Components Used

| Component      | Quantity | Description               |
|----------------|----------|---------------------------|
| 555 Timer IC (U1) | 1        | Astable multivibrator     |
| Capacitors (C1, C2) | 2      | 10nF, 100µF               |
| Resistors (R1-R4) | 4        | 100Ω, 1kΩ                 |
| Potentiometer (RV1) | 1     | 100kΩ (adjusts frequency) |
| LEDs (D1-D3)     | 3        | Green LEDs                |
| Transistor (Q1)  | 1        | BC547 NPN                 |
| Power Supply (BAT1) | 1     | 5V DC battery             |

## 🛠️ Circuit Description

- The 555 Timer is configured in **Astable Mode** with a capacitor (C2) and a resistor/potentiometer network to generate a square wave.
- The output pin (pin 3) of the 555 Timer is connected to the base of the BC547 transistor via a 1kΩ resistor (R1).
- The transistor acts as a switch that controls the LEDs (D1-D3).
- Each LED has its own 100Ω current-limiting resistor (R2, R3, R4).

## 🖥️ Simulation

This circuit is designed and simulated using **Proteus**. To run the simulation:

1. Open Proteus software.
2. Load the `.pdsprj` file (if available).
3. Click the play button to simulate the circuit and observe the LED blinking.

## 📁 Files

- `README.md` - Project documentation.


## 🔧 Adjusting Blinking Rate

You can control the blinking frequency using the 100kΩ potentiometer (RV1). Increasing the resistance slows down the blinking, while decreasing it speeds it up.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork the repository and submit pull requests for improvements or suggestions.

---

Enjoy building and experimenting with the 555 Timer! 🚀
