# musescore-tin-whistle
This repo provides an extra instrument file for adding High Tin Whistle types to Musescore.

The High Tin Whistle, which is a metal 6 hole Flageolet, comes in various tunings. These are
listed in order of decreasing physical size:
* "B♭ Tin Whistle" tuned to key B♭, also used for keys Cm and E♭
* "C Tin Whistle" tuned to C, also for Dm and F
* "D Tin Whistle" tuned to D, also for Em and G
* "E♭ Tin Whistle" tuned to E♭, also for Fm and A♭
* "F Tin Whistle" tuned to F, mainly used for Gm as F can be played on a C whistle
* "G Tin Whistle" tuned to G, mainly used for Am as G can be played on a D whistle

Tuning to D is by far the most common, so "Tin Whistle" is the same as "D Tin Whistle".

## Install
The file `tin-whistle.xml` needs to be installed as an instrument extension using the MuseScore
menu. Use the same file for both MuseScore version 2.x and MuseScore version 3.x :

### MuseScore 2.x
1. copy file `tin-whistle.xml` to `Documents/MuseScore2/Extensions/tin-whistle.xml`
2. within Musescore menu, navigate to `MuseScore` then `Preferences...` then `Score` tab
3. in the Default Files panel, add the file to 'Instrument List 2' extension by:
4. browsing to `Documents/MuseScore2/Extensions/tin-whistle.xml` and add to 'Instrument List 2'

### MuseScore 3.x
1. copy file `tin-whistle.xml` to `Documents/MuseScore3/Extensions/tin-whistle.xml`
2. within Musescore menu, navigate to `MuseScore` then `Preferences...` then `Score` tab
3. in the Default Files panel, add the file to 'Instrument List 2' extension by:
4. browsing to `Documents/MuseScore3/Extensions/tin-whistle.xml` and add to 'Instrument List 2'

You may now add a tin whistle staff using MuseScore menu item `Edit` then `Instruments...`, 
where MuseScore lists these extra instruments under 'World Music' 'Woodwinds'.

Once a tin whistle staff is added to the score there is no need to keep the instrument
file `tin-whistle.xml` in the 'Instrument List 2' extension.

The score `tin_whistle_range_test.mscz` is an example score showing all the High Tin Whistle staves.
