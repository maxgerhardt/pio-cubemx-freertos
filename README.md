# PlatformIO CubeMX FreeRTOS example  

1. Install [PlatformIO Core](http://docs.platformio.org/page/core.html)
2. Download this repository. 
3. Extract ZIP archive
4. Run these commands:

```sh
    # Build project
    > platformio run

    # Upload firmware
    > platformio run --target upload

    # Build specific environment
    > platformio run -e nucleo_l152re

    # Upload firmware for the specific environment
    > platformio run -e nucleo_l152re --target upload

    # Clean build files
    > platformio run --target clean
```