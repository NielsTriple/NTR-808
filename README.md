# NTR-808
These files are for Fl-Studio only!
A full emulation (or at least a well attempted try) of the infamous Roland TR-808.

- About
- Knobs and switches
- Also included
- Extra info
- Links that helped me
- By me

1) ABOUT:

I've created the NTR-808 to use it myself, so it's tuned to, plugged according to, and looks to my liking.
I've tried to make it (able to) sound as 1980's and 90's as I could, but it may not sound like the 808 that you want, out of the box. But it can. Probably. 
As you can see in the flp files, the NTR-808 can do the Geh, do crack, and get high! But most of the knobs are added to create your own sound, so the modern producer can make it bounce as well.
I've read as much as I could about the 808, went over the original 808 manual and electronic drawings, found some usable info in old TS-808 threads, wrestled through an actual scientific publication to figure out how to do the cymbal (and hihats, but mainly the cymbal, because the hihats just followed along), watched lots of youtubes, watched an actual movie /docu, and since this is my first ever Patcher preset, there was also a lot of trial and error.
As for the looks, I hope you'll like the classic red, orange, yellow and white, with the subtle MC-303 grey as much as I do ;)

---

2) KNOBS AND SWITCHES:

- SideChain
SideCh.Am: (Sidechain amount) how deep the BD volume should be cut.
SideCh.Dec: (Sidechain decay) how sharp or fading the cut should be.
SD switch: Lets the BD be sidechained by the SD.
CP switch: Lets the BD be sidechained by the CP.
Note: Both can be on, at the same time, and there will be one sidechain signal created.

- BassDrum
C5 + Oct. 1 / Oct. 2 tuned
Gain: Volume control
Tone: Controls the frequency for lowpass filter
Punch: Add or remove punch
Decay: Lengthen or shorten the decay
Detune: BD decay will slide down in pitch
Overdr.: (Overdrive) Gently overdrive the BD
Sub: Controls the frequency for highpass filter
Key selecter: Select in which key the BD should play.
Note: Key selecter also affects the pitch of the tuned BD octaves 1 and 2.

- SnareDrum
C#5 + Oct. 3 / Oct. 4 tuned
Gain: Volume control
Tone: Add or remove tonal part of the snare
Snappy: Add or remove snappy part of the snare
Decay: Lengthen or shorten the decay
Sizzle: Add or remove timbre.

- HiTom / HiConga + MidTom / MidConga + LowTom / LowConga
D5 + D#5 + E5
Gain: Volume control
Tone: Adjust filter
Tuning: Tune the pitch up or down
Decay: Lengthen or shorten the decay.

- RimShot / CLaves
F5
Gain: Volume control
Tone: Adjust filter
Tuning: Tune the pitch up or down
Decay: Lengthen or shorten the decay.

- handClaP / MAracas
F#5
Gain: Volume control
Tone: Adjust filter
Dec.Imp: CP more claps on impact, MA attack control
Dec.Tail: CP lengthen or shorten the tail, MA decay control
Note: if you adjust attack and decay just right, and automate the gain contol, you can create shaker sounds, which the original 808 didn't have.

- CowBell
G5 + Oct. 6 / Oct. 7 tuned
Gain: Volume control
Tone: Adjust bandpass filter
Buzz: Give more buzz to the bell
Decay: Lengthen or shorten the decay
Phase: Phase the L&R channels

- Cymbal
G#5
Gain: Volume control
Tone: Add whitenoise
Tuning: Tune pitch up or down
Decay: Lengthen or shorten the decay

- OpenHihat + ClosedHihat 
A5 + A#5
Gain: Volume control
Tone: Add whitenoise
Tuning: Tune pitch up or down
Decay: Lengthen or shorten the decay

---

3) ALSO INCLUDED:

Three flp files with classic 808 beats, and 1 with a custom trap(?) beat.
- NTR-808 can do the Geh
  (Marvin Gaye - Sexual healing)
- NTR-808 can do crack
  (Whitney Houston - I wanna dance with somebody)
- NTR-808 can get high
  (Afroman - Because I got high)
- NTR-808 can bounce
  (Quick something by me)

---

4) EXTRA INFO:

- Midi port 10: NTR-808 will respond according to GM (General MIDI) Drum Map, in stead of the notes presented in the GUI.
The original 808 didn't have a MIDI interface, but I've found manuals that said how to add it, and how to map the available sounds accordingly.

- Audio output: 
1 - Every sound has it's own mixer insert. The BD is always on the insert channel selected for Patcher, and SD is one to the right, then the Toms and Conga's, etc.
So if patcher is on ins. 1, BD is on ins. 1, and SD will be on 2, Toms/Congas on 3, etc. If you don't set Patcher to a specific insert, BD will be on the master, SD will be on ins. 1, Toms/Congas on 2, etc.
2 - The audio comes out raw and uncompressed. You might need to tame the beast with some compression or limiters (or whatever you use in your fx chain) when you use it. 

- Automation: All knobs and sliders can be automated. Right click, and activate button. Right click again and automate away!

- Checkboxes: They do nothing, other than blink. They function as LED, and not as button. Nothing will happen if you select or unselect one.

- All FL editions: All generators and effects used in this patch, are available for all FL editions (SimSynth challenge, anyone?)
I've read somewhere that the Fruity edition doesn't come with pianoroll, and I don't know if that's true. If so, you might have to get a bit hacky, but this one is also for the budget beatmakers!

- Name: I just merged my initials (NT) with the TR.

- Free: This preset is free, but I've put a lot of time and effort into it. So if you enjoy it, or use it in a release, feel free to buy me a coffee (or a car) ;) 

--- 

5) LINKS THAT HELPED ME:
https://www.researchgate.net/publication/267630051_The_TR-808_Cymbal_a_Physically-Informed_Circuit-Bendable_Digital_Model

https://www.kvraudio.com/product/ts_808_by_tactile_sounds

https://www.musicradar.com/how-to/how-to-recreate-classic-analogue-drum-sounds-in-your-daw-and-with-hardware

https://en.m.wikipedia.org/wiki/General_MIDI#/media/File%3AGM_Standard_Drum_Map_on_the_keyboard.svg

---

6) by Niels Triple, May 2022
