# flight-sim-controls
data dump for flight sim controls mappings


# Sync Custom.binds
Every time there is a keybinding change, a Custom file is generated. So just copy/backup the Custom files.
cp /c/Users/cevaris/AppData/Local/Frontier\ Developments/Elite\ Dangerous/Options/Bindings/Custom* /c/Users/cevaris/workspace/flight-sim-controls/EliteDangerous/

if lost keyboard bindings in ED, just make sure CH Products is in Map Mode; not Direct/Off-Mode
Is CH Control Manager actually still showing the hotas is in Mapped mode? C010 is probably the USB id exposed by the synthetic mapped device, so if they unmapped for some reason, the game wouldn't recognise the direct-mode devices.

https://www.reddit.com/r/EliteDangerous/comments/5893sn/bindings_not_showing_up_in_game_but_present_in/

