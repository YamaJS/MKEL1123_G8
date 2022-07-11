# MKEL1123_G8_Milestone4

MKEL1123_G8_Milestone4 is a mini-project of ADVANCED MICROPROCESSOR SYSTEM(MKEL1123) that will be completed by a group of UTM master students. The final goal of this mini-project is to implement a complete digital system using STM32 board. This project will be separated into 6 different milestones and in this milestone 1 subfolder, we will be focusing on the milestone 1 deliverables.

# Group Member:
> - SIN HAU JIE 
> - HOR CHONG SAN
> - CHEONG MEI YUET 

# Milestone 4 :  

## Description 

## Procedure:
> 1. Install STM32CubeIDE and all necessary drivers.
> 2. Connect the ST-LINK debugger to the Black Pill (STM32) board.
> 3. Connect an external LED to the Port PB0 of the Black Pill board if there is no onboard LED to be used.

### 4a. FOR RTOS:
> 5. During Setup of .ioc file, Click Pinout and Configuration tab -> Click Middelware → Click FREERTOS → Select Interface to CMSIS_V1
> 6. Configuration → Advanced Settings → USE_NEWLIB_REENTRANT (Enabled) 
> 7. Configuration → Tasks and Queues → Assign Task Name, Entry Function and Priority as shown below:
  - Task Name: Temp_High, Priority: osPriorityNormal
  - Task Name: Temp_Check, Priority: osPriorityBelowNormal
  - Task Name: LCD_Display, Priority: osPriorityBelowNormal1
> 8. Click Pinout and Configuration tab -> Click Connectivity -> Click I2C1 -> In I2C tab -> Select I2C
> 9. Click Pinout and Configuration tab -> Click SYS -> Click Debug -> Click Serial Wire
> 10. Press ctrl + s to proceed to main.c code.
> 11. Connect I2C pin for LCD as shown below :
> ![image](https://user-images.githubusercontent.com/45865379/178192590-65df64fd-2fbf-4df0-afa1-09242f420e2e.png)
> 12. Upload the code to stm32 black pill and proceed to observe the behaviour on the LCD screen display.

### 4b. FOR DHT11_LCD:

## Tools 

...