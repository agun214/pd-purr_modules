# pd-purr_modules
collection of pd music tools. MIDI, gamepad, OSC input. Tools: clock, arp, euclidean seq, CV generator and mic-input-to-CV 

(in active development, no promises of functionality)

this is for my mobile setup, which includes: 

  -analog monosynth 

  -mic input for vocals or CV modulation

  -two audio-tailored raspberry pi 4s, one sequencing midi/cv, one hosting vsts/fx 
  
      MIDI/CV Pi:   -HiFiBerry soundcard (HAT)
                    -controlled with touchOSC+ps3 gamepad
                    -generates midi/cv data according to clock
                    -internal/external clock options
                    -audio output goes to monosynth CV inputs (LFO Rate and Filter Cutoff)
                    -midi output > midisport2x2 > uc33 mixer midi in > Calf Fluidsynth
  
      VST/FX Pi:    -Scarlett Focusrite 2i2 usb audio interface 
                    -runs Fluidsynth and other Calf plugins
                    -8 channel mixer for volumes/velocities
                    -uc33 midi input also sent to MIDI/CV Pi


(will add details as project progresses)
