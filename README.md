STM32F3discovery-Template
=========================

The intent of this code template is to allow you to get up GCC and the ST STM32F3 Discovery Board up and running quickly. The template is structured with a common makefile at the top level of the directory heirarchy and project directories below this level. The project directories can be separated from the template with an adjustment to a makefile path variable. 

# Dependencies: 
## Compiler
You should be able to use any arm-none-eabi-xxx compiler. However, the testing on this template was done with the Codesourcery Lite Package. 

[Codesourcery arm-none-eabi Tools] (http://www.mentor.com/embedded-software/sourcery-tools/sourcery-codebench/editions/lite-edition/arm-eabi)

## Libraries
[STM32F3 Discovery Firmware Libraries Provided by ST](http://www.st.com/internet/com/SOFTWARE_RESOURCES/SW_COMPONENT/FIRMWARE/stm32f3discovery_fw.zip)

## Hardware Link
The makefile.common file use the st-flash utility for downloading which is part of the texane/stlink github project. 
[texane/stlink github project](https://github.com/texane/stlink)

# Relevant Makefile Variables
## Makefile.common
### TOOLROOT:
Installation directory for your compiler. 
### LIBROOT:
Installation of the ST Library package for F3 board

## Makefile
### TEMPLATEROOT:
Location of the Makefile.common file. 






