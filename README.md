# STM32



官网

https://www.st.com/content/st_com/en/stm32cube-ecosystem.html

微雪STM32CubeMX系列教程

https://www.waveshare.net/study/article-629-1.html

Mac：[**STM32CubeIDE**](https://www.st.com/en/development-tools/stm32cubeide.html)

Win：[**STM32CubeMX**](https://www.st.com/en/development-tools/stm32cubemx.html) + Keil5 + STLink

[Getting Started with STM32 and Nucleo Part 1: Introduction to STM32CubeIDE and Blinky – Digi-Key](https://www.youtube.com/watch?v=hyZS2p1tW-g)

[KiCad STM32 + USB + Buck Converter PCB Design and JLCPCB Assembly (Update)](https://www.youtube.com/watch?v=C7-8nUU6e3E)

[Phil’s Lab](https://www.youtube.com/c/PhilS94)

https://www.digikey.com/en/maker/search-results?y=13825c8674444e22884d8d26197819d1&k=STM32&g=relevance&page=1

STM32CubeIDE缩放：DPI缩放设置为 系统（增强），但是会导致代码编辑器代码稍稍模糊

最终解决方案：用MX配置，IDE编辑代码并Debug。





Digikey教程

[Getting Started with STM32 - Introduction to STM32CubeIDE](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-introduction-to-stm32cubeide/6a6c60a670c447abb90fd0fd78008697)

[Getting Started with STM32 - I2C Example](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-i2c-example/ba8c2bfef2024654b5dd10012425fa23)

[Getting Started with STM32 - Working with ADC and DMA](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-working-with-adc-and-dma/f5009db3a3ed4370acaf545a3370c30c)

[Getting Started with STM32 - Introduction to FreeRTOS](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-introduction-to-freertos/ad275395687e4d85935351e16ec575b1)

[TinyML: Getting Started with STM32 X-CUBE-AI](https://www.digikey.com/en/maker/projects/tinyml-getting-started-with-stm32-x-cube-ai/f94e1c8bfc1e4b6291d0f672d780d2c0)

[Getting Started with STM32 - How to Use SPI](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-how-to-use-spi/09eab3dfe74c4d0391aaaa99b0a8ee17)

[Getting Started with STM32 - Working with ADC and DMA](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-working-with-adc-and-dma/f5009db3a3ed4370acaf545a3370c30c)

[Getting Started with STM32 - Timers and Timer Interrupts](https://www.digikey.com/en/maker/projects/getting-started-with-stm32-timers-and-timer-interrupts/d08e6493cefa486fb1e79c43c0b08cc6)

[Making a Temperature Logger with the Adafruit Feather STM32F405 Express](https://www.digikey.com/en/maker/projects/making-a-temperature-logger-with-the-adafruit-feather-stm32f405-express/11ea860d54074a19bb75cb6425e6d0b0)

Related Videos: 

Getting Started with STM32 and Nucleo Part 1: Introduction to STM32CubeIDE and Blinky [https://www.youtube.com/watch?v=hyZS2...](https://www.youtube.com/watch?v=hyZS2p1tW-g) 

Getting Started With STM32 and Nucleo Part 2: How to Use I2C to Read Temperature Sensor TMP102 [https://www.youtube.com/watch?v=isOek...](https://www.youtube.com/watch?v=isOekyygpR8) 

Getting Started With STM32 and Nucleo Part 3: FreeRTOS - How To Run Multiple Threads w/ CMSIS-RTOS [https://www.youtube.com/watch?v=OPrcp...](https://www.youtube.com/watch?v=OPrcpbKNSjU) 

Getting Started With STM32 & Nucleo Part 4: Working with ADC and DMA [https://www.youtube.com/watch?v=EsZLg...](https://www.youtube.com/watch?v=EsZLgqhqfO0) 

Getting Started With STM32 and Nucleo Part 5: How to Use SPI [https://www.youtube.com/watch?v=eFKeN...](https://www.youtube.com/watch?v=eFKeNPJq50g) 

Getting Started with STM32 and Nucleo Part 6: Timers and Timer Interrupts https://www.youtube.com/watch?v=VfbW6nfG4kw



Programming the Adafruit Feather STM32F405 Express with STM32CubeIDE [https://www.youtube.com/watch?v=gOjzs...](https://www.youtube.com/watch?v=gOjzs4y5hWA) 

TinyML: Getting Started with STM32 X-CUBE-AI [https://www.youtube.com/watch?v=crJcD...](https://www.youtube.com/watch?v=crJcDqIUbP4) 

Related Project Links: Getting Started with STM32 - Timers and Timer Interrupts - [https://www.digikey.com/en/maker/proj...](https://www.youtube.com/redirect?event=video_description&v=VfbW6nfG4kw&redir_token=QUFFLUhqbVZuVkZMSlVreEt5MU5fOVhvaHd3WlE3eWlFQXxBQ3Jtc0tuQjh4ZHIyOVdwRTBvM192UWhTLUc1Z0QtVF8zdjRfWE10bldDdk0tSEVvc3VxbkR4TmRjcVJIV3FzVEZSZFRRZ2lNRHQzREhSVEtySnltZWUycE5QSkRFbkVPQmFMYzJORThHTDZvdVloN25GTXdvSQ%3D%3D&q=https%3A%2F%2Fwww.digikey.com%2Fen%2Fmaker%2Fprojects%2Fgetting-started-with-stm32-timers-and-timer-interrupts%2Fd08e6493cefa486fb1e79c43c0b08cc6)



## STM32笔记

USB Port Busy解决：用另一个串口UART1，接上USB转串口，用MobaXterm打开这个串口就好了。