
Personal Arduino Package Index
==============================

Contains the JSON files that the Arduino IDE uses to identify board definitions
available for download.

Add the following URL to your `Additional Boards Manager URL` list in the Arduino
IDE preferences:

```
https://raw.githubusercontent.com/kimballa/arduino-pkg-index/main/package_gremblor_index.json
```

You will need to install the official Arduino MegaAVR board definitions first to install
the appropriate compiler toolchain.

This includes resources to point the Arduino IDE at the 
[megaavr board variant definition](https://github.com/kimballa/megaavr-boarddefs)
for my [ATMega809 breakout board](https://github.com/kimballa/ATMega809-breakout).
