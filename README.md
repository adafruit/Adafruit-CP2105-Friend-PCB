## Adafruit CP2105 Friend - USB to Dual UART Serial Converters PCB

<a href="http://www.adafruit.com/products/6065"><img src="assets/6065.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit CP2105 Friend - USB to Dual UART Serial Converters. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6065

### Description

On our first Pentium 120 tower (purchased at PCs for Everyone on Thorndike st in Cambridge Mass) came with two DE-9 serial ports on the back: COM1 and COM2. Perfect for connecting a mouse and maybe a modem. Nowadays, long gone are the days of parallel ports and serial ports. Now the USB port reigns supreme! But USB is hard, and you just want to transfer your every-day serial data from two serial ports to a single USB port without the complexity of a hub. What now? Enter the Adafruit CP2105 Friend!

The CP2105 is very similar to the CP2102N. Except, instead of having a single serial UART port, it has two. One is 'standard' and one is 'enhanced' - you'll get both enumerated when plugging in this device, without any hub required!

The Enhanced port can do:

* Data formats supported:
- Data bits: 5, 6, 7, and 8
- Stop bits: 1, 1.5, and 2
- Parity: odd, even, mark, space, no parity
* Baud rates: 300 bps to 2.0 Mbps
* 320 Byte receive and transmit buffers
* Modem control signals: CTS, RTS, DTR, DSR and RI

The Standard port can do:

* Data format: 8 data bits, 1 Stop bit
Parity: Even, Odd, No parity
* Baud rates: 2400 bps to 921600 bps
* 288 Byte receive and transmit buffers
* Modem control signals: CTS, RTS, DTR, DSR and RI

Like the CP2102N breakout, we have USB C connector and the same overall shape, but there are some significant changes. The pins are going to be totally different because we have two UARTs, one on either 'side' of the board. The left side is the Enhanced port, right side is the Standard port. We don't have extra GPIO pads and no indicator LEDs. Also the bottom row is a 'minimal' output of just the two RX/TX pads and power pins.

We like the CP210x series because it has better driver support than the CH340 and can do very high speeds, and variable speeds without stability issues. Compared to the FT232RL and FT231X, the CP210x has the same capabilities or better, at a great price! 

Each order comes with a fully assembled and tested board. We give you some pin header strip, solder it in to plug it into a breadboard and get access to all the pins.

For Linux you won't need a driver. For Windows, it will automatically grab the driver from Windows Update. For Mac OS X you can check out SiLabs driver page for the latest and greatest.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
