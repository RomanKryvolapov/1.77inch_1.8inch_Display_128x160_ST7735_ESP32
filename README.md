<h1>Simple Platformio / CLion project</h1>
<h2>1.77 / 1.8 inch 128x160 TN display with ST7735 controller</h2>
<h2>ESP32 DEVKIT V1 board</h2>
<h3>Pins:</h3>
<p>PIN_SPI_RST = 2, Used for ST7735</p>
<p>PIN_SPI_DC = 4, Used for ST7735</p>
<p>PIN_SPI_CS_SS = 15, Used for ST7735</p>
<p>PIN_SPI_SDA_SDI_DARA_IN_MOSI = 13, Used for ST7735</p>
<p>PIN_SPI_SDO_DATA_OUT_MISO = 12</p>
<p>PIN_SPI_SCK_CLK_SCL_SCLK = 14, Used for ST7735</p>
<p>PIN_DISPLAY_BRIGHTNESS = 5, can be used, if support</p>
<p>PIN_I2C_SDA = 21</p>
<p>PIN_I2C_SCL = 22</p>
<p>PIN_UART_TX = 17</p>
<p>PIN_UART_RX = 16</p>

<p>for blue display without indications, pins:</p>
<p>1->8 = LED -> CS -> RS(DC,A0) -> RES -> SDA -> SCK -> VCC -> GND</p>
<p>red and black (touch) display DC = A0</p>

![1!](https://github.com/RomanKryvolapov/2.4_2.8_LCD_320x240_ILI9341_ESP32/blob/master/Display.jpg "1")