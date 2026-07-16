# STM32F401CCU6 LED Blink Project 🚀

My first STM32 project using the STM32F401CCU6 Black Pill board and ST-LINK debugger.

## Hardware
- STM32F401CCU6 Black Pill
- ST-LINK V2
- USB Cable

## Software
- STM32CubeIDE
- STM32CubeProgrammer
- STM32 HAL Library

## Objective
Configure GPIO and blink the onboard LED connected to **PC13**.

## Features
- Successful STM32CubeIDE setup
- ST-LINK programming and debugging
- GPIO output configuration
- Verified active-low onboard LED operation

## Project code files

[Click here to access the full project code](code)

## Project Images
![Click here to check out the project images](images/IMG_20260716_173105_374)

## Project Demo Video

[Click here to access the project Demostration video](https://youtu.be/IygqJTG93ew?si=02OfjJvdtl3c_619)

## Code
```c
while (1)
{
    HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_13);
    HAL_Delay(500);
}
```

## Result
✅ Onboard LED blinking successfully.

This project marks the beginning of my STM32 and bare-metal embedded systems journey.
