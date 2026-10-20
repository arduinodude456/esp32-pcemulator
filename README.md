# PCEmulator for ESP32
## The idea
Since Inwas using a cheap yellow display without PSRAM and VGA, FabGL's PCEMULATOR won't work for me. So I decided to make my own Emulator.
## No PSRAM needed
Unlike other emulators, esp32-pcemulator runs huge Programs, for example Windows 3.0, without needing PSRAM. Only 512 KB of RAM are required.
That means, a bare ESP-WROOM-32, like it is found in the CYDs, can actually run it.
The only thing you'll need is a SD Card("TF Card").

## Support
esp32-pcemulator supports MS-DOS 6.22 and Windows 3.0 
and many other stuff like FreeDOS, and every program that runs on 8086 arch.

# To prove it
See the Pictures in /picture
![image of a cyd running windows setup](https://github.com/arduinodude456/esp32-pcemulator/blob/main/picture/IMG_20261020_161203635.jpg)

## Example test
The supplied file mindows.img 
Load it into drive A:. Then click reset.
The file contains MS-DOS 5 and a minimal version of Windows 3.0

The Emulator also runs a full version but it is too big so I cant upload it :) 
Just install MS Dos on hard drive and then windows.
