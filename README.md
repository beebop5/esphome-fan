# esphome-fan
ESPHome based ceiling fan controller for a 24V DC UVW fan

This project started because I bought 2 ceiling fans for a property I am renovating, then bought 2 Sonoff iFan04-h controllers. After flashing the new iFan04-h's, I realised that they can only control 220-240v AC fans - the fans I had bought were 24v DC (UVW as I found from disassembling the controller.

So, I felt I have 2 options; 1) replace the remote with a blaster (433Mhz perhaps?) this is controlled from either home assistant or an ESP32, or 2) build a new controller. Option 1 seems like it would be easier, but feel a little 'hacky', and I don't like the 1-way nature of the communication. Option 2 seemed like it was going to be more difficult, but i wanted to explore it.

As it turns out, this was easier than expected. UVW motor controllers can be aquired inexpensively (AliExpress link below)

