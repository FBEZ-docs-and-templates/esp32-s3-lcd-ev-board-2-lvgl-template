# esp32-s3-lcd-ev-board-2-lvgl-template
Template for starting with the ESP32-S3-LCD-EV-Board-2 based on esp_bsp but stripped from additional configurations. 


## How to use

1. Build, flash to check everything is fine. Specify target and port if missing.
2. Exit from the monitor (`CTRL+T, CTRL+X`)
3. Create component in the `components` folder (`cd components` , `idf.py create-component <component_name>`) or use vscode create component
4. Go to the component `main.c` and add `#include "lvgl.h"`


