# ESP8266-Led-Matrix-Web-Draw
Draw on your LED Matrix using a web interface

![stream](https://i.imgur.com/O87D9ze.jpg)

![stream](https://i.imgur.com/F2ybAhu.jpg)

Still a WIP project

Feel free to reach out if you have any questions:

- [YouTube](https://www.youtube.com/c/BrianLough)
- [Twitch](https://www.twitch.tv/brianlough)
- [Twitter](https://twitter.com/witnessmenow)

Huge thanks to David Watts for providing the base for the web interface code! Check out his channel [here](https://www.youtube.com/user/MrDavidJWatts)

### Instructions

- Instructions for getting set up with the display can be found [here](https://youtu.be/YvU_ZfF7vs4). Wring [here](https://raw.githubusercontent.com/witnessmenow/LED-Matrix-Mario-Display/master/Wiring.png)
- Download this repo
- Open up "DisplayWithWebscokets" in the Arduino IDE.
- Update secret.h with your WiFi details.
- Upload the sketch to your board.
- Check what IP address it received via the serial monitor.
- Edit "Web Interface/index.html" to change the IP address `new WebSocket("ws://192.168.1.31:81");`
- Open index.html with your web browser
- start drawing!

### Next steps

- Put web interface on ESP8266
- ~~Add support for dragging the cursor to paint many squares~~ - Done
- Add ability to sync display to web interface
- Add the ability to load/save drawings
- Add Export to code option
- Too many to list them all!
