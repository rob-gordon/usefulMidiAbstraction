<< Useful Midi Abstraction >>

This feature extractor was built in Cycling 74's Max. It's meant for use with wekinator (https://github.com/fiebrink1/wekimini), and is available at https://github.com/rob-gordon/usefulMidiAbstraction

This project can be used to extract the following features from incoming midi streams or midi files:

1. The size of the chord being played / Number of notes held down
2. The average center around which notes are being played
3. The relative speed of the performance measured by the time between note-on events.
4. The "movement" measured by the distance jumped between consecutive notes.

This repo includes both the editable max patch as well as the compiled, standalone version. As such, it requires either the full or standalone version of Cycling 74's Max, which is available here: https://cycling74.com/downloads/#.VzsRspN96Rs