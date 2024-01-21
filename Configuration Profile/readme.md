The [profile.bin](profile.bin) file is one method can be used to trigger/set advanced settings that are not availiable in the WebUI of the stock Firmware. Most of the settings are pretty much self explanatory, feel free to leave a commit to further describe these settings!

The configuration profile can be extracted on firmwares above 2018xxxxx by accessing the URL http://192.168.10.1/profile.bin (HTTP-GET)
In order to apply an edited profile, you need to HTTP-POST the edited profile.bin file to the same path.
In Case you are not able to fetch the "profile.bin" file from your own device, there is a working example [here](profile.bin).

