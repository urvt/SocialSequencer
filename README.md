# SocialSequencer

## SOUNDBANKS
```
previous: makefilename ~/Desktop/Imported2/Bank_%d/Board_%%d/Slot_%%%%%%%%d/Material_%%%%d.wav
new     : makefilename ~/Soundbanks/Bank_%d/Board_%%d/Slot_%%%%%%%%d/Material_%%%%d.wav
Slot_0 - Bass
Slot_1 - Synth
Slot_2 - Kick
Slot_3 - Snare
Slot_4 - Hat
```
 
## FOR AUTOSTART:
```
#!/bin/bash
sleep 30

pd -verbose -audiodev 5 -mididev 3 -listdev -open /home/pi/Documents/SocialSequencerRaspberry/SocialSequencer_v0_6.pd
```