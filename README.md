# OLED-DISPALY
## AIM: Display Front Left Door Status on the OLED using I2C
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
## Procedure[# OLED-DISPALY
## AIM: Display Front Left Door Status on the OLED using I2C
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

1. Connect the **S32K144 Development Board** and OLED display to the system.
2. Open **S32 Design Studio** and create/open the S32K144 project.
3. Configure the **OLED display** for **I2C communication**.
4. Configure the required **I2C pins (SDA and SCL)**.
5. Configure the **Front Left Door status input** as a GPIO digital input.
6. Initialize the **GPIO and I2C peripherals**.
7. Initialize the OLED display using the I2C interface.
8. Read the Front Left Door status periodically.
9. If the door is open, display **"Front Left Door: OPEN"** on the OLED.
10. If the door is closed, display **"Front Left Door: CLOSED"** on the OLED.
11. Build the project and check for compilation errors.
12. Download the program to the **S32K144** board.
13. Run the program and change the Front Left Door input status.
14. Observe the corresponding door status displayed on the OLED.

---
## OUTPUT

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/241534fd-3353-4eec-8e2d-15262f2ff457" />






---

## Result

The **Front Left Door status was successfully displayed on the OLED using I2C communication**. The OLED displayed **"Front Left Door: OPEN"** when the door was open and **"Front Left Door: CLOSED"** when the door was closed, confirming successful GPIO input and I2C OLED operation.
](https://github.com/dineshvishnu696-cmyk/potentiometer-value-display-using-ADC-UART/tree/main)


1. Connect the **S32K144 Development Board** and OLED display to the system.
2. Open **S32 Design Studio** and create/open the S32K144 project.
3. Configure the **OLED display** for **I2C communication**.
4. Configure the required **I2C pins (SDA and SCL)**.
5. Configure the **Front Left Door status input** as a GPIO digital input.
6. Initialize the **GPIO and I2C peripherals**.
7. Initialize the OLED display using the I2C interface.
8. Read the Front Left Door status periodically.
9. If the door is open, display **"Front Left Door: OPEN"** on the OLED.
10. If the door is closed, display **"Front Left Door: CLOSED"** on the OLED.
11. Build the project and check for compilation errors.
12. Download the program to the **S32K144** board.
13. Run the program and change the Front Left Door input status.
14. Observe the corresponding door status displayed on the OLED.

---
## OUTPUT







---

## Result

The **Front Left Door status was successfully displayed on the OLED using I2C communication**. The OLED displayed **"Front Left Door: OPEN"** when the door was open and **"Front Left Door: CLOSED"** when the door was closed, confirming successful GPIO input and I2C OLED operation.
