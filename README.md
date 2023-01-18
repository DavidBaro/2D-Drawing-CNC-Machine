# 2D-Drawing-CNC-Machine
### A 2D drawing machine using arduino:
In this project two stepper motors from two CD ROMs are reused and are used for x-axis and y-axis coordination and a servo motor for z-axis coordination and the following arrangements were done:
1. select a suitable arduino board and a motor driver for it.
2. Install the motor driver library for arduino - "*Adafruit-Motor-Shield-Library-master*" can be installed from the Arduino IDE itself.
3. Install [Inkscape-0.48.5-1-win32](https://inkscape.org/release/inkscape-0.48/?latest=1), a vector graphics editor, and add the G-code extension to it for converting the images into G-code to be able to provide the coordinates to the arduino using a Processing IDE.
4. Install [Processing IDE](https://github.com/processing/processing4/releases/download/processing-1290-4.1.2/processing-4.1.2-windows-x64.zip) to process the coordinates from the G-code generated and provide them to the arduino in order to make CNC machine work.
5. Make a template, a canvas size where the image is drawn, relative to the range of the x-axis and y-axis movements, so that the template can be used as a guide for the size of the canvas where the image is to be drawn.
