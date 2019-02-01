# STM Pinout
(LQFP64)

### General Logic Nets

| NET        |Correct Pin| Pin #| Error | Essential Conflict |
|------------|:------:|:----:|-------| -        |
|**BOOT0**   | BOOT0  | 60   | -     | -        |
|**nRST**    | nRST   | 7    | -     | -        |
|**GPIO 1**  | PA0    | 14   | *PA1* | -        |
|**GPIO 2**  | PA1    | 15   | *PA2* | -        |
|**VBUS S**  | PA6    | 22   | -     | -        |
|**USB DM**  | PA11   | 44   | -     | -        |
|**USB DP**  | PA12   | 45   | -     | -        |
|**SWDIO**   | PA13   | 46   | -     | -        |
|**SWCLK**   | PA14   | 49   | -     | -        |
|**CAN R**   | PB8    | 61   | -     | -        |
|**CAN D**   | PB9    | 62   | -     | -        |

### Motor Logic Nets

| NET        |Correct Pin| Pin #| Error | Essential Conflict |
|------------|:------:|:----:|-------|----------|
|**M TEMP**  | PC5    | 25   | *PA3* | -        |
|**M SO1**   | PC0    | 0    | *PA1* | -        |
|**M SO2**   | PC1    | 9    | *PA2* | -        |
|**M ENC Z** | PC9    | 40   | *PA7* | -        |
|**M ENC A** | PB4    | 56   | *PA8* | -        |
|**M ENC C** | PB5    | 57   | *PA9* | -        |
|**M AH**    | PA8    | 61   | *PC0* | -        |
|**M BH**    | PA9    | 42   | *PC1* | -        |
|**M CH**    | PA10   | 43   | *PC2* | -        |
|**M AL**    | PB13   | 34   | *PC3* | -        |
|**M BL**    | PB14   | 35   | *PC4* | -        |
|**M CL**    | PB15   | 36   | *PC5* | -        |
|**EN GATE** | PB12   | 33   | *PC6* | -        |
|**nFAULT**  | PD2    | 54   | *PC7* | -        |
|**SPI SCK** | PC10   | 51   | -     | -        |
|**SPI MISO**| PC11   | 52   | -     | -        |
|**SPI MOSI**| PC12   | 53   | -     | -        |
|**M nCS**   | PC13   | 2    | -     | -        |
