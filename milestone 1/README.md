# MKEL1123_G8_Milestone1 

MKEL1123_G8_Milestone1 is a mini-project of ADVANCED MICROPROCESSOR SYSTEM(MKEL1123) that will be completed by a group of UTM master students. The final goal of this mini-project is to implement a complete digital system using STM32 board. This project will be separated into 6 different milestones and in this repository, we will be focusing on the milestone 1 deliverables.

# Group Member:
> - SIN HAU JIE 
> - HOR CHUN SHANG
> - CHEONG MEI YUET 

# Milestone 1 : STM32 Familiarization 

## Description <img src= "https://user-images.githubusercontent.com/45865379/168462608-a1b06cee-bb4d-4be5-b836-d714153c4c0f.png" width="25" height="25">:
> Milestone 1 is purposed to verify the usability of the STM32 board with basic led blink code. A Black Pill STM32F411CEU6 board along with the ST-LINK V2 programmer are used. To test the cortex M4 chip, a basic c code which blinks the C13 on board LED for 1 second (1Hz) interval is compiled and programmed into the black chip. The on board LED should be expected to blink with 1 second interval with the connection of the ST-LINK V2 programmer or a standard USB type C cable. The c code is written and programmed into the black pill using STM32CodeIDE software.  

## Objective <img src= "https://user-images.githubusercontent.com/45865379/168462578-eb967319-b4d0-4b30-9f85-dff5dd5dbc51.png" width="25" height="25">:
> 1. To get familiar with the STM32 IDE tool and firmaware development.
> 2. To verify the usability of the chosen STM32 board.
> 3. To get accustom with reporting milestones on GitHub.

## Tools <img src= "https://user-images.githubusercontent.com/45865379/168462520-36c43467-2e6a-490a-bc73-97718746e810.png" width="25" height="25">:

> - Black Pill (STM32F411CEU6) <br /> <img src= "https://user-images.githubusercontent.com/43127923/168484496-1c579d80-2780-4d89-a25e-1528c6f6a567.jpeg" width="100" height="150">
> - ST-LINK <br /> <img src= "https://user-images.githubusercontent.com/43127923/168484459-5615faba-0774-4376-af45-6eedd8631bbd.jpeg" width="100" height="150">
> - STM32CubeIDE 
> - USB cables (Optional)

## Installation <img src= "https://user-images.githubusercontent.com/43127923/168483419-f4ee28e3-7ccb-4fe0-9474-4dbfe7ac460d.png" width="25" height="25">: 
> 1. Install STM32CubeIDE and all necessary drivers.
> 2. Connect the ST-LINK debugger to the Black Pill (STM32) board.
> 3. Connect an external LED to the Port PB0 of the Black Pill board if there is no onboard LED to be used.

## Image of the board <img src= "https://user-images.githubusercontent.com/45865379/168462315-d77f724f-cd3c-4fa1-aa57-307de5195c1c.png" width="50" height="50">:
>The image below shows the board is powered up when the onboard led light up. After the board is successfully powered up, the board can be programmed to blink the LED at 1 Hz with the written C code.<br /> <img src= "https://user-images.githubusercontent.com/45865379/168460083-41721760-5304-4927-95de-9f458c13acdd.png" width="250" height="240">
## YouTube link <img src= "https://user-images.githubusercontent.com/45865379/168462426-274bd5cd-7767-42ee-b1c2-61a3c919d559.png" width="25" height="25"> : 
> - https://youtu.be/GOmmGItwFvQ

## References <img src= "https://user-images.githubusercontent.com/43127923/168483161-affd204b-4baf-4c14-890d-1eb46fc409bc.png" width="25" height="25">: 
> - https://www.youtube.com/watch?v=kXg467nVd_A&t=3s&ab_channel=NizarMohideen-MicroPeta
> - https://wiki.st.com/stm32mcu/wiki/STM32StepByStep:Step2_Blink_LED
