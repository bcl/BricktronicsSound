BricktronicsSound
=================

**BricktronicsSound v1.2 - A software library for LEGO NXT sound sensors.**

More details at http://www.wayneandlayne.com/bricktronics/

**To Download**
* Click the "Clone or download" button on the upper-right side of this page below the pink bar, then select "Download ZIP". Rename the uncompressed folder BricktronicsSound. Check that the BricktronicsSound folder contains BricktronicsSound.cpp and BricktronicsSound.h
* Place the BricktronicsSound library folder into your `<arduinosketchfolder>/libraries/` folder. You may need to create the libraries subfolder if this is your first installed library. Restart the Arduino IDE.

**API Highlights**
* `BricktronicsSound(uint8_t inputPin, uint8_t dbPin, uint8_t dbaPin)` - Constructor
* `void begin(void)` - Call the begin function in your setup() function
* `uint16_t value(void)` - Basic sensor read function, scale is 0-1023, but usually 250-980.
* `void setMode(uint8_t mode)` - Switch between DB and DBA mode (DBA = DB adjusted for human hearing)
* More API details in [API.md](API.md)

**If you want to use sound sensors with your Bricktronics Shield or Megashield, you may also be interested in these libraries:**
* [BricktronicsShield Arduino Library v1.2](https://github.com/wayneandlayne/BricktronicsShield)
* [BricktronicsMegashield Arduino Library v1.2](https://github.com/wayneandlayne/BricktronicsMegashield)

_Wayne and Layne, LLC and our products are not connected to or endorsed by the LEGO Group. LEGO, Mindstorms, and NXT are trademarks of the LEGO Group._

