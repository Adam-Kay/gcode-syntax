gcode-syntax (dark mode)
============

G-code syntax highlighting for CNC or 3D Printing for Notepad++ with UDL2.0, modified from [/robEllenberg/gcode-syntax](https://github.com/robEllenberg/gcode-syntax) to have better colors for dark mode.

### To install this syntax highlighter:

1. Make sure you have [Notepad++ 6.x.x](https://notepad-plus-plus.org/downloads/) or above installed to use the new user defined languages
2. Clone this repository or just download the appropriate the `.xml` file (that's all you need): 
	- For CNC machines, use [`gcode-cnc.xml`](https://github.com/Adam-Kay/gcode-syntax/blob/master/gcode-cnc.xml)
	- For 3D printing[^1], use [`gcode-3dp.xml`](https://github.com/Adam-Kay/gcode-syntax/blob/master/gcode-3dp.xml)
3. In Notepad++, in the **Language** tab, go to **User-Defined Language** → **Define Your Language...**
4. Click "Import", then browse to the downloaded `.xml` file. If you see "Import was successful", then the G-code syntax highlighter is installed.

[^1]:G and M codes derived from [Marlin documentation](https://marlinfw.org/docs/gcode/G000-G001.html)