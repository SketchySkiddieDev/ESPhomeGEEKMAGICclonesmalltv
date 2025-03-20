# ESPhomeGEEKMAGICclonesmalltv
my ESPhome configuration for the ESP8266 based clone of the GEEKMAGIC small tv. 

Features:

      15s refresh rate (is this a feature? it's adjustable. No way to make the frame buffer work as far as I know due to space constraints, so it will redraw the screen in an ugly manner no matter what. 15s seemed good enough)
      Clock that is readable from across the room, in 12h format by default
      date displayed with 3 letter code for day of week (e.g. "Thu" then date in MM/DD format

      Roadmap: VERY basic weather display


Currently it waits for the air purifier in the bedroom to turn on, when it does "party mode" is engaged and it turns the display text green

