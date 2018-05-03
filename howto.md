## There are a few ways of making sounds and music in QBasic.


The first command is `BEEP`. `BEEP` just beeps and is used as an alert.


Next is the `SOUND` command. `SOUND` plays a frequency for a specified duration

- Frequency 37 to 32767

- Duration 0 to 65535


Finally, there is `PLAY`. Here are some settings for `PLAY`:


`O` - Octave (0 - 6): O6

`<` or `>` - Moves Up or Down One Octave

`P` - Pauses (1 - 64): P1   Pause Whole Note

`T` - Tempo (32 - 255) in Quarter Notes Per Minute: T120

`A`, `B`, `C`, `D`, `E`, `F`, `G` - Plays The Note in the Current Octave

Playing Length(1 - 64): `C2` Plays a C Half Note

`+` or `#` Makes The Preceding Note Sharp

`-` (Minus) Makes the Preceding Note Flat



NOTE: QBasic uses the internal speaker to play sounds and music. Many computers do not come with an internal PC speaker. To get around this problem use DOSBox or QB64.
