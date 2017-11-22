# Exent-Bootmapper
1. Download Bootmapper client from https://www.dropbox.com/s/3bn9flirkb49ahz/BootMapperClient.zip?dl=0 and the hex files from this rep.
2. Open bootmapper client
3. Short LEFT CTRL on your PCB with tweezers while plugging into a DIRECT usb port (You'll hear a sound if it connects successfully)
4. Go to Options, click Firm Up and select the ps2avrGB_NKRO.hex file. Wait for it to finish.
5. Go back to Keymapper, and click Download. If you followed the guide correctly, you'll see BAD on all columns and rows.
6. Select Load keymap_part.hex or json and select the Exent 65 hex file.
7. Tick Reboot after uploading and select Upload.
8. DONE. This is essentially how to flash all bootmapper firmware pcbs. 

# Underglow RGB Leds
1. Once you're done flashing, go to Options. 
2. Select Connect
3. Change the number of RGB LEDs to 20.
4. Select Rainbow or any other option than Off.
5. You can configure the brightness, colour and speed transition here. 

