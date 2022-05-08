# ESP-IDF Components library
I want to use and add to this libary, but I've taken out some of the components I don't expect to ever use.  This will evolve as my needs for this library changes.
In the mean time, feel free to use this collection of other people's code for your own needs if you've run across this repo!
## Components!

### ADC/DAC libraries

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **ads111x**              | Driver for ADS1113/ADS1114/ADS1115 and ADS1013/ADS1014/ADS1015 I2C ADC           | BSD-3   | `esp32`, `esp8266` | Yes
| **hx711**                | Driver for HX711 24-bit ADC for weigh scales                                     | BSD-3   | `esp32`, `esp8266` | No
| **mcp342x**              | Driver for 18-Bit, delta-sigma ADC MCP3426/MCP3427/MCP3428                       | BSD-3   | `esp32`, `esp8266` | Yes
| **mcp4725**              | Driver for 12-bit DAC MCP4725                                                    | BSD-3   | `esp32`, `esp8266` | Yes
| **pcf8591**              | Driver for 8-bit ADC and an 8-bit DAC PCF8591                                    | BSD-3   | `esp32`, `esp8266` | Yes

### Common libraries

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **color**                | Common library for RGB and HSV colors                                            | MIT     | `esp32`, `esp8266` | Yes
| **esp_idf_lib_helpers**  | Common support library for esp-idf-lib                                           | ISC     | `esp32`, `esp8266` | Yes
| **framebuffer**          | RGB framebuffer component                                                        | MIT     | `esp32`, `esp8266` | Yes
| **i2cdev**               | ESP-IDF I2C master thread-safe utilities                                         | MIT     | `esp32`, `esp8266` | Yes
| **lib8tion**             | Math functions specifically designed for LED programming                         | MIT     | `esp32`, `esp8266` | Yes
| **noise**                | Noise generation functions                                                       | MIT     | `esp32`, `esp8266` | Yes
| **onewire**              | Bit-banging 1-Wire driver                                                        | MIT     | `esp32`, `esp8266` | No

### Current and power sensors

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **ina219**               | Driver for INA219/INA220 bidirectional current/power monitor                     | BSD-3   | `esp32`, `esp8266` | Yes
| **ina260**               | Driver for INA260 precision digital current and power monitor                    | BSD-3   | `esp32`, `esp8266` | Yes
| **ina3221**              | Driver for INA3221 shunt and bus voltage monitor                                 | ISC     | `esp32`, `esp8266` | Yes

### GPIO expanders

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **mcp23008**             | Driver for 8-bit I2C GPIO expander MCP23008                                      | BSD-3   | `esp32`, `esp8266` | Yes
| **mcp23x17**             | Driver for I2C/SPI 16 bit GPIO expanders MCP23017/MCP23S17                       | BSD-3   | `esp32`            | Yes
| **pca9557**              | Driver for PCA9537/PCA9557 remote 4/8-bit I/O expanders for I2C-bus              | BSD-3   | `esp32`, `esp8266` | Yes
| **pcf8574**              | Driver for PCF8574 remote 8-bit I/O expander for I2C-bus                         | MIT     | `esp32`, `esp8266` | Yes
| **pcf8575**              | Driver for PCF8575 remote 16-bit I/O expander for I2C-bus                        | MIT     | `esp32`, `esp8266` | Yes
| **tca95x5**              | Driver for TCA9535/TCA9555 remote 16-bit I/O expanders for I2C-bus               | BSD-3   | `esp32`, `esp8266` | Yes

### Input device drivers

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **button**               | HW timer-based driver for GPIO buttons                                           | MIT     | `esp32`, `esp8266` | Yes
| **encoder**              | HW timer-based driver for incremental rotary encoders                            | BSD-3   | `esp32`, `esp8266` | Yes
| **ls7366r**              | Driver for LS7366R Quadrature Encoder Counter                                    | MIT     | `esp32`            | Yes

### LED drivers

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **led_strip**            | RMT-based driver for WS2812B/SK6812/APA106 LED strips                            | MIT     | `esp32`            | Yes
| **led_strip_spi**        | SPI-based driver for SK9822/APA102 LED strips                                    | MIT     | `esp32`, `esp32c3`, `esp8266` | Yes

### Light sensors

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **bh1750**               | Driver for BH1750 light sensor                                                   | BSD-3   | `esp32`, `esp8266` | Yes
| **tsl2561**              | Driver for light-to-digital converter TSL2561                                    | BSD-3   | `esp32`, `esp8266` | Yes
| **tsl2591**              | Driver for light-to-digital converter TSL2591                                    | MIT     | `esp32`, `esp8266` | Yes
| **tsl4531**              | Driver for digital ambient light sensor TSL4531                                  | BSD-3   | `esp32`, `esp8266` | Yes

### Magnetic sensors

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **hmc5883l**             | Driver for 3-axis digital compass HMC5883L                                       | BSD-3   | `esp32`, `esp8266` | Yes
| **qmc5883l**             | Driver for QMC5883L 3-axis magnetic sensor                                       | BSD-3   | `esp32`, `esp8266` | Yes

### Other misc libraries

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **ds3502**               | Driver for nonvolatile digital potentiometer DS3502                              | BSD-3   | `esp32`, `esp8266` | Yes
| **example**              | An example component                                                             | ISC     | `esp32`, `esp8266` | Yes
| **hd44780**              | Driver for HD44780 compatible LCD text displays                                  | BSD-3   | `esp32`, `esp8266` | No
| **max7219**              | Driver for 8-Digit LED display drivers, MAX7219/MAX7221                          | BSD-3   | `esp32`            | Yes
| **pca9685**              | Driver for 16-channel, 12-bit PWM PCA9685                                        | BSD-3   | `esp32`, `esp8266` | Yes
| **rda5807m**             | Driver for single-chip broadcast FM radio tuner RDA5807M                         | BSD-3   | `esp32`, `esp8266` | Yes
| **tca9548**              | Driver for TCA9548A/PCA9548A low-voltage 8-channel I2C switch                    | BSD-3   | `esp32`, `esp8266` | Yes
| **tda74xx**              | Driver for TDA7439/TDA7439DS/TDA7440D audioprocessors                            | MIT     | `esp32`, `esp8266` | Yes
| **ultrasonic**           | Driver for ultrasonic range meters, e.g. HC-SR04, HY-SRF05                       | BSD-3   | `esp32`, `esp8266` | No
| **wiegand**              | Wiegand protocol receiver                                                        | BSD-3   | `esp32`, `esp8266` | No

### Real-time clocks

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **ds1302**               | Driver for DS1302 RTC module                                                     | BSD-3   | `esp32`, `esp8266` | No
| **ds1307**               | Driver for DS1307 RTC module                                                     | BSD-3   | `esp32`, `esp8266` | Yes
| **ds3231**               | Driver for DS1337 RTC and DS3231 high precision RTC module                       | MIT     | `esp32`, `esp8266` | Yes
| **pcf8563**              | Driver for PCF8563 real-time clock/calendar                                      | BSD-3   | `esp32`, `esp8266` | Yes

### Temperature sensors

| Component                | Description                                                                      | License | Supported on       | Thread safety
|--------------------------|----------------------------------------------------------------------------------|---------|--------------------|--------------
| **aht**                  | Driver for AHT10/AHT15/AHT20 temperature and humidity sensor                     | BSD-3   | `esp32`, `esp8266` | Yes
| **bh1900nux**            | Driver for BH1900NUX temperature sensor                                          | BSD-3   | `esp32`, `esp8266` | Yes
| **bme680**               | Driver for BME680 digital environmental sensor                                   | BSD-3   | `esp32`, `esp8266` | Yes
| **bmp180**               | Driver for BMP180 digital pressure sensor                                        | MIT     | `esp32`, `esp8266` | Yes
| **bmp280**               | Driver for BMP280/BME280 digital pressure sensor                                 | MIT     | `esp32`, `esp8266` | Yes
| **dht**                  | Driver for DHT11, AM2301 (DHT21, DHT22, AM2302, AM2321), Itead Si7021            | BSD-3   | `esp32`, `esp8266` | No
| **ds18x20**              | Driver for DS18B20/DS18S20 families of 1-Wire temperature sensor ICs             | BSD-3   | `esp32`, `esp8266` | No
| **hdc1000**              | Driver for HDC1000 temperature and humidity sensor                               | BSD-3   | `esp32`, `esp8266` | Yes
| **hts221**               | Driver for HTS221 temperature and humidity sensor.                               | ISC     | `esp32`            | Yes
| **lm75**                 | Driver for LM75, a digital temperature sensor and thermal watchdog               | BSD-3   | `esp32`, `esp8266` | Yes
| **max31725**             | Driver for MAX31725/MAX31726 temperature sensors                                 | BSD-3   | `esp32`, `esp8266` | Yes
| **max31865**             | Driver for MAX31865 resistance converter for platinum RTDs                       | BSD-3   | `esp32`            | Yes
| **mcp960x**              | Driver for MCP9600/MCP9601, thermocouple EMF to temperature converter            | BSD-3   | `esp32`, `esp8266` | Yes
| **mcp9808**              | Driver for MCP9808 Digital Temperature Sensor                                    | BSD-3   | `esp32`, `esp8266` | Yes
| **ms5611**               | Driver for barometic pressure sensor MS5611-01BA03                               | BSD-3   | `esp32`, `esp8266` | Yes
| **sht3x**                | Driver for Sensirion SHT30/SHT31/SHT35 digital temperature and humidity sensor   | BSD-3   | `esp32`, `esp8266` | Yes
| **sht4x**                | Driver for Sensirion SHT40/SHT41/SHT45 digital temperature and humidity sensor   | BSD-3   | `esp32`, `esp8266` | Yes
| **si7021**               | Driver for Si7013/Si7020/Si7021/HTU2xD/SHT2x and compatible temperature and humidity sensors | BSD-3   | `esp32`, `esp32c3`, `esp8266` | Yes
| **tsys01**               | Driver for precision digital temperature sensor TSYS01                           | BSD-3   | `esp32`, `esp8266` | Yes

## Library maintainers
This fork of the library is not going to be maintained more than for what I need, but checkout the real UncleRus/esp-idf-lib for the true library

## Credits

- [Tomoyuki Sakurai](https://github.com/trombik), developer of the LM75 and
  SK9822/APA102 drivers, author of the RTOS SDK ESP82666 support, master CI
- [Gunar Schorcht](https://github.com/gschorcht), developer of SHT3x, BME680
  and CCS811 drivers
- [Brian Schwind](https://github.com/bschwind), developer of TS2561 and
  TSL4531 drivers
- [Andrej Krutak](https://github.com/andree182), developer of BH1750 driver
- Frank Bargstedt, developer of BMP180 driver
- [sheinz](https://github.com/sheinz), developer of BMP280 driver
- [Jonathan Hartsuiker](https://github.com/jsuiker), developer of DHT driver
- [Grzegorz Hetman](https://github.com/hetii), developer of DS18B20 driver
- [Alex Stewart](https://github.com/astewart-consensus), developer of DS18B20 driver
- [Richard A Burton](mailto:richardaburton@gmail.com), developer of DS3231 driver
- [Bhuvanchandra DV](https://github.com/bhuvanchandra), developer of DS3231 driver
- [Zaltora](https://github.com/Zaltora), developer of INA3231 driver
- [Bernhard Guillon](https://gitlab.com/mrnice), developer of MS5611-01BA03 driver
- [Pham Ngoc Thanh](https://github.com/panoti), developer of PCF8591 driver
- [Lucio Tarantino](https://github.com/dianlight), developer of ADS111x driver
- [Julian Dörner](https://github.com/juliandoerner), developer of TSL2591 driver
- [FastLED community](https://github.com/FastLED), developers of `lib8tion`,
  `color` and `noise` libraries
- [Erriez](https://github.com/Erriez), developer of MH-Z19B driver
- [David Douard](https://github.com/douardda), developer of MH-Z19B driver
- [Nate Usher](https://github.com/nated0g), developer of SCD30 driver
- [Josh Kallus](https://github.com/Jkallus), developer of LS7366R driver
- [saasaa](https://github.com/saasaa), developer of HTS221 driver
