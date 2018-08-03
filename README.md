# drum-machine-patterns

## About

This is a project by [Aarón Montoya-Moraga](http://montoyamoraga.io/).

This project is inspired by the book *200 Drum Machine Patterns* by René-Pierre Bardet, a collection of 200 contemporary rhythm patterns to program into your drum machine.

This project is a digital MIDI transcription of the original book.

## Original notation

The original book uses the following abbreviations:

* AC: Accent
* BD: Bass drum
* SD: Snare Drum
* LT: Low tom
* MT: Medium tom
* HT: High tom
* CH: Closed hi-hat
* OH: Open hi-hat
* CY: Cymbal
* RS: Rim shot
* CP: Clap
* CB: Cowbell

The unit of time used is a sixteenth note (black fill), or a sixteenth rest (white fill).

Most patterns are in 4/4 time, which means there are four quarter notes in a measure.

The sixteenth-note unit used by drum machines allows each beat to be broken into four subdivisions.

1 measure = 4 quarter notes

1 quarter note = 4 sixteenth notes

1 measure = 16 sixteenth notes

The notation only specifies when each drum is hit, not its duration.

## [General MIDI](https://en.wikipedia.org/wiki/General_MIDI#Percussion)

Channel 10 is usually reserved for percussion instruments only.

* 35 Bass Drum 2
* 36 Bass Drum 1
* 37 Side Stick/Rimshot
* 38 Snare Drum 1
* 39 Hand Clap
* 40 Snare Drum 2
* 41 Low Tom 2
* 42 Closed Hi-hat
* 43 Low Tom 1
* 44 Pedal Hi-hat
* 45 Mid Tom 2
* 46 Open Hi-hat
* 47 Mid Tom 1
* 48 High Tom 2
* 49 Crash Cymbal 1
* 50 High Tom 1
* 51 Ride Cymbal 1
* 52 Chinese Cymbal
* 53 Ride Bell
* 54 Tambourine
* 55 Splash Cymbal
* 56 Cowbell
* 57 Crash Cymbal 2
* 58 Vibra Slap
* 59 Ride Cymbal 2
* 60 High Bongo
* 61 Low Bongo
* 62 Mute High Conga
* 63 Open High Conga
* 64 Low Conga
* 65 High Timbale
* 66 Low Timbale
* 67 High Agogô
* 68 Low Agogô
* 69 Cabasa
* 70 Maracas
* 71 Short Whistle
* 72 Long Whistle
* 73 Short Güiro
* 74 Long Güiro
* 75 Claves
* 76 High Wood Block
* 77 Low Wood Block
* 78 Mute Cuíca
* 79 Open Cuíca
* 80 Mute Triangle
* 81 Open Triangle

## Conventions for this project

This library follows the mapping of the instrument Roland TR-09:

* 36 BD Bass drum
* 37 RS Rim shot
* 38 SD Snare drum
* 39 CP Clap
* 42 CH Closed hihat
* 43 LT Low tom
* 46 OH Open hihat
* 47 MT Mid tom
* 49 CY Crash cymbal
* 50 HT High tom


## Patterns from the book 200 Drum machine patterns

### Rock 1

4/4, quarter note 112-139

#### Measure A

|Drum|01|02|03|04|05|06|07|08|09|10|11|12|13|14|15|16|
|----|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|AC *| 0| 0| 0| 0| 1| 0| 0| 0| 0| 0| 0| 0| 1| 0| 0| 0|
|CY  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|CH *| 1| 0| 0| 0| 1| 0| 0| 0| 1| 0| 0| 0| 1| 0| 0| 0|
|OH  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|HT  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|MT  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|SD *| 0| 0| 0| 0| 1| 0| 0| 0| 0| 0| 0| 0| 1| 0| 0| 0|
|RS  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|LT  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|CP  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|CB  | 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0| 0|
|BD *| 1| 0| 0| 0| 0| 0| 1| 0| 1| 0| 0| 0| 0| 0| 0| 0|
