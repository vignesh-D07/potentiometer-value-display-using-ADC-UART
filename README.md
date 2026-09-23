# potentiometer-value-display-using-ADC-UART
## AIM:Initialize the ADC, read the on-board potentiometer in software-trigger mode and transmit the raw count through UART. Convert the ADC value into millivolts and compare both outputs. 
---
---

## Apparatus Required

| S. No. | Apparatus / Software | Specification |
|:---:|---|---|
| 1 | Microcontroller Development Board | **NXP S32K144 Development Board** |
| 2 | IDE | **S32 Design Studio** |
| 3 | Programming Language | **Embedded C** |
| 4 | SDK | **S32K144 SDK** |
| 5 | LED | On-board LED / External LED |
| 6 | Programmer / Debugger | On-board Debugger / OpenSDA |
| 7 | USB Cable | For programming and power supply |

---
## Procedure

1. Connect the **S32K144 Development Board** to the computer.
2. Open **S32 Design Studio** and create/open the S32K144 project.
3. Configure the **ADC module** for the potentiometer input.
4. Set the ADC to **software-trigger mode**.
5. Configure the required **UART module** for serial communication.
6. Initialize the ADC and UART peripherals.
7. Start an ADC conversion through software.
8. Read the **raw ADC count** after the conversion is completed.
9. Convert the ADC count into **millivolts** using the ADC reference voltage and resolution.
10. Transmit both the **raw ADC value and calculated voltage** through UART.
11. Open **PuTTY** and observe the transmitted values.
12. Rotate the potentiometer gradually and record the corresponding ADC count and voltage.
13. Compare the raw ADC count with the calculated voltage at different potentiometer positions.
14. Verify that the ADC count and voltage increase or decrease according to the potentiometer position.

---
## OUTPUT

<img width="472" height="218" alt="image" src="https://github.com/user-attachments/assets/e59b4c83-9e81-4851-b550-629c8467a176" />

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/38372154-4e48-4880-a472-7e3ddc61b588" />






---

## Result

The **ADC was successfully initialized in software-trigger mode**, and the on-board potentiometer value was read correctly. The **raw ADC count and corresponding voltage in millivolts** were successfully transmitted through UART. The comparison confirmed that the ADC count varies proportionally with the potentiometer voltage.
