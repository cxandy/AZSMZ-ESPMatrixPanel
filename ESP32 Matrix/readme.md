# AZSMZ ESP32 Matrix
![AZSMZ ESP32 Matrix](/ESP32Photos/ESP32MATRIX-A12-1024.jpg)

![AZSMZ ESP32 Matrix](/ESP32Photos/ESP32MATRIX-A3.jpg)
![AZSMZ ESP32 Matrix](/ESP32Photos/ESP32MATRIX-A4.jpg)

## https://github.com/mrfaptastic/ESP32-RGB64x32MatrixPanel-I2S-DMA

By default the pin mapping is as follows (defaults defined in ESP32-RGB64x32MatrixPanel-I2S-DMA.h).

```
 HUB 75 PANEL              ESP 32 PIN
+-----------+   
|  R1   G1  |    R1  -> IO17      G1  -> IO2
|  B1   GND |    B1  -> IO16
|  R2   G2  |    R2  -> IO4      G2  -> IO15
|  B2   GND |    B2  -> IO13
|   A   B   |    A   -> IO26      B   -> IO27
|   C   D   |    C   -> IO14      D   -> IO12
| CLK   LAT |    CLK -> IO25      LAT -> IO33
|  OE   GND |    OE  -> IO32      GND -> GND
+-----------+
```

```
#define R1_PIN 17
#define G1_PIN 2
#define B1_PIN 16
#define R2_PIN 4
#define G2_PIN 15
#define B2_PIN 13
#define A_PIN 26
#define B_PIN 27 
#define C_PIN 14
#define D_PIN 12
#define E_PIN -1
#define LAT_PIN 33
#define OE_PIN 32
#define CLK_PIN 25
```
