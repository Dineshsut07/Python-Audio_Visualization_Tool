# Python-Audio_Visualization_Tool
You can create a real-time audio visualization tool using Python. In this project we will use a GUI(Graphical User Interface) tool named tkinter to create a window to plot grapth / audio visualizer plots.


What the program does? 

- It uses your default mic to take voice as input
- Creates a window and show plot for measuring frame rate
- Takes Binary data > convert to integers > make up np array > offset it by 127 and 128
- Finlly update the girure canvas and show the final graph
``` 
### Requirements

* Python
* Python Libraries: `pyaudio` `os` `struct` `numpy` `matplotlib.pyplot` `time` `tkinter`
