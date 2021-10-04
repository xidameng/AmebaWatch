# AmebaWatch
A Smart Watch Project that uses RTL8722DM_MINI

# Connection
The pin connection to the GC9A01 SPI IPS LCD display is in the sketch code @Line 14

# Preparation needed
1. You need to install the zip library found in this folder to your Arduino IDE to correctly configure for SPI on MINI
2. Put the "Time_Audio_16khz_16bit_Mono.wav" file into an SD card and slot the SD card into the RTL8722DM_MINI's SD card holder
3. Connect a speaker/headphone to RTL8722DM_MINI via the on-board audio jack


# TODO
[x] Display time
[x] Play voice recoding at the specific time
[ ] Improve the UI
[ ] Use NTP to retrieve network time
[ ] Implement Google Text-to-Speech 

