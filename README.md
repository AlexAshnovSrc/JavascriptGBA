## Browser Compatibility
The current version of JavascriptGBA is known to work in the following web browsers:

* Safari 6.0 or newer
* Chrome 22 or newer
* Firefox 25 or newer (slow)

The following web browsers also work, but will have degraded feature sets:

* Firefox 15 or newer (no sound, slow)
* Opera 12.1x or newer (no sound, slow)
* Internet Explorer 10 or newer (no sound, slow, pixelated display does not work)
* Chrome 20, 21 (pixelated display does not work)

The following browsers will not work:

* Safari 5.1.x or older (no File API for uploading games into JavaScript)
* Firefox 14 or older (no DataView, used for memory)
* Internet Explorer 9 or older

All other browsers are untested.

## Feature List
Currently, every part of the Game Boy Advance hardware, save for some lesser used features and the link cable are implemented.

The emulator also has these features:

* Downloadable and uploadable savegames
* Screenshots
* Pausing the emulation
* Support for gamepaks that contain a realtime clock (e.g. Pokemon Ruby and Sapphire)

Features that may be implemented in the future include:

* Savestates
* Remappable controls
* Gamepad support
* Link cable over Web Sockets
* Cheat code support
* Fullscreen support
* Support for gamepaks that have other sensors (e.g. WarioWare Twisted!, Boktai)
