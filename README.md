# MIDI_Visualizer
## ![Example Usage](/SNK_vid.gif)
## Inputs
```
python ./MIDI_project.py --midiname ./test.mid --tbs 1.2 --tbe 1.4 --spd 5 --rcd Y
```
In command line, MIDI_Visualizer uses a parser to parse commands from the user.

```--midiname``` takes the path to the midifile to visualize. \n
```--tbs``` takes a float of time (seconds) before the visualizer receives the first message. \n
```--tbe``` takes a float of time (seconds) before the visualizer ends the program after receiving the final message. \n
```--spd``` takes an int and affects the downward speed of the notes. \n
```--rcd``` takes a Y/N input and affects whether the program records and outputs the visualization as an mp4 file to the video folder. \n
