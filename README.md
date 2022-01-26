# Keithley2010-Instrument-Controller
Labview Application for data-acquisition using Keithley 2010 7.5digit DMM

This is a Labview application that polls and collects data from a Keithley 2010. Interface is via GPIB using standard visa libraries.
Command interface via SCPI commands.

![image](https://user-images.githubusercontent.com/1159017/151247609-34a9f85d-7e2f-4437-8ad6-f35c5c3525c4.png)

The software provides instrument control of mode, various setup parameters, etc..
There are 3 real-time graphs of scrolling data, stacked data, and histogram spreads.
Data can be saved as image files, csv, xls.

Primarily written for long term observance of drift on precision voltage references. I have another version for the Agilent 3458A for even higher resolution (8.5 digits) that I'll push up in the near future. The software will poll the instrument at the highest possible rate consistent with user settings.

Still some work to be done on this, but functional and stable. Im currently working on adding a Allen-variance plot to the mix that I'll push when fully tested.
