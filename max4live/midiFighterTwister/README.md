
# controller / gesture looper
for DJTechTools Midi Fighter Twister and max4live

![image](./gestures.png)

- fighterTwisterM4L_1-64.amxd - max4live device for the first two banks of knobs on the Twister
- fighterTwisterM4L_65-127.amxd - max4live device for banks 3 and 4
- fighterTwisterM4L-all.amxd - max4live device for all the banks of knobs at once
- fighterTwisterM4L.mfs - mapping to be sent to Midi Fighter Twister via Midi Fighter Utility (save your config!)
- *.maxpat files - abstractions required for the device to function

# installation

- put the folder anywhere, make sure *.maxpat files and *.amxd files are in the same folder

# how to use

- add one of the devices (.amxd files) to an empty midi track
- set track input and output to midi fighter twister, set midi channel to 1
- twist knobs, map parameters
- recording mode: press and hold any knob and twist
- upon release, playback begins immediately. time your loops well!
- visual feedback is provided both in ableton and on the hardware itself
- any side button on the right side: next bank
- any side button on the left side: previous bank
- short click on the knob clears buffer
- buffer length: 20 seconds

# known issues

- in the bank 4, two knobs are usable but non-recordable (they are not illuminated)
- according to internet, when loading the device for the first time, you might need to delete it from ableton session and reinsert it. you will see this as green scopes not moving as you twist the knobs. this is due to the way max abstractions are treated in max4live. personally, i have not experienced that, but YMMV

made by humans (no llms)
