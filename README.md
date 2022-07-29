# RP2040-NRF24-Sensor-Node
A low-power Raspberry RP2040 + nRF24L01+ Sensor Node with LiPo Charger and Protection Circuitry

![image](https://user-images.githubusercontent.com/6614616/180988876-144fc949-0bf1-442e-b0da-cc705b372a3d.png)

## EasyEDA Project
You can find the EasyEDA Schematic and Board Layout in the *hardware* folder.

## Pinout

| RP2040 GPIO   | Function            |
| ------------- | ------------------- |
| GP0           | nRF24 IRQ           |
| GP1           | nRF24 CE            |
| GP2           | nRF24 SCK           |
| GP3           | nRF24 MOSI          |
| GP4           | nRF24 MISO          |
| GP5           | nRF24 CSN           |
| GP6           | ADC_BATT_EN         |
| GP7           | VEXT_EN             |
| GP8           | SHT30 SDA           |
| GP9           | SHD30 SCL           |
| GP10          | SPI1_SCK_I2C1_SDA   |
| GP11          | SPI1_MOSI_I2C1_SCL  |
| GP12          | SPI1_MISO_I2C0_SDA  |
| GP13          | SPI1_CSN_I2C0_SCL   |
| GP14          | Pair Button         |
| GP15 - 24     | JST PH 12 pos       |
| GP26          | ADC_BATT            |
