# pd-line6M9

Line6 M9 Stompbox modeler unit is awesome.

The Idea of this patches is to give it even more awesomeness by being able to control it with your computer (or programs in your computer or other midi devices connected to your computer), you can also use it as a dumb midi controller to control stuff in your computer if you want to.

## Requirements

* pure data extended [https://puredata.info/downloads/pd-extended]
* Line 6 M9 Stompbox Modeler
* Midi interface with midi-in and midi-out ports and cables.

## Contents

* m9_looperControl.pd - This has some toggles and bang objects to control the Looper mode.
* m9_tapIn - This is an abstraction that activates a bang control when you step on the Tap pedal (you can use this one to control some stuff on your computer and still use the effects in the unit as normal)
* m9_pedalIn - This is an abstraction you can add to your patches to control them with your m9 (This is more usefull if you don't want to use the effects of the unit, but rather use the pedals to control your software, so you should bypass the m9 effects loop) (m9_pedalIn) is also included in this abstraction.
