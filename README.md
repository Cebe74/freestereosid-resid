The FreeStereoSID Adapter or "Free Stereo SID" board is a SID socket adapter board for a Teensy 4.0, which you can then plug into a C64 SID socket, like a SwinSID, ArmSID or FPGASID.

The PCB board can be bought at https://www.uni64.com/en/p/freestereosid-adapter

Matthias, the author and designer of this board also provides a SID emulator which is still in development and an early version: http://data.uni64.com/free_stereo_sid/FreeStereoSID_source.zip

This project uses FrankBoesing's Teensy-reSID instead, which itself is based on resid: http://www.zimmers.net/anonftp/pub/cbm/crossplatform/emulators/resid/index.html ~ the main INO file however comes from Matthias' implementation.

Please note: if you're looking for a stable replacement of the MOS 6581 or 8580 SID music chip, you should use an AmrSID or FPGASID instead. If you do happen to have a Teensy 4.0, then it can be fun to emulate a SID with it :-)
