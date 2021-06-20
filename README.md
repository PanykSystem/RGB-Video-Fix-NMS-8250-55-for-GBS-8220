# RGB-Video-Fix-NMS-8250-55-for-GBS-8220

The GBS-8220 + LM 1881 does not synchronize with the video signals, because the video output of the SCART (pin 19) has no correct signal at 15Khz, fault of the IC302 delay circuit. it is solved by removing the JI309 bridge, connecting the pin 3 of the JI309 to the test point TP301
