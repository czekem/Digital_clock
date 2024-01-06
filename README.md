Customizing the Clock Display

The digital clock can be customized by changing the display format and appearance. Here are some examples:

   - To display only the hours, minutes, and seconds (without AM/PM), remove the "%p" from the display_time variable in line 11.
   - To display only the hours and minutes, remove the "%S" from the display_time variable.
   - To display the clock in 24-hour format, use "%H" instead of "%I" in the display_time variable.
   - To change the font, color, or background color of the clock, modify the properties of the digi_clock Label object.

For more detailed information on formatting options, please refer to the official Tkinter documentation.
All informations about time-formats, you can find here:
https://docs.python.org/3/library/time.html

Possible fonts that can be used are listed here (you need to have tkinter libraries):
https://stackoverflow.com/questions/39614027/list-available-font-families-in-tkinter

Possible colors of frame and it's back can be found here:
https://www.gkindex.com/python-advanced/python-fonts-and-colors.jsp

Tkinter documentation:
https://docs.python.org/3/library/tkinter.html




Needed libraries:
- tkinter // to install it just type pip install tk in your IDE terminal ( for conda and other systems here is instruction : https://www.geeksforgeeks.org/how-to-install-tkinter-in-windows/ )
- time // it's installed in Python as already with the 'base', so you just need to write 'import time'



