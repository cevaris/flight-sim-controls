# flight-sim-controls
data dump for flight sim controls mappings


# Sync ED-Prod.binds
ln -sf /c/Users/cevaris/workspace/flight-sim-controls/ED-Prod.binds /c/Users/cevaris/AppData/Local/Frontier\ Developments/Elite\ Dangerous/Options/Bindings/ED-Prod.binds

if lost keyboard bindings in ED, just make sure CH Products is in Map Mode; not Direct/Off-Mode
Is CH Control Manager actually still showing the hotas is in Mapped mode? C010 is probably the USB id exposed by the synthetic mapped device, so if they unmapped for some reason, the game wouldn't recognise the direct-mode devices.
