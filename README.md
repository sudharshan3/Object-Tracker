# Object tracking system using raspberry pi
________________________________________________________________________________________________________________________

# Initial Setup

1. Make Rpi connections: Keyboard, Mouse, Webcam, ethernet or wifi dongle, Display via HDMI, Power

2. Power on your Rpi

3. Boot into raspbian GUI on your Rpi (Raspbian boot to GUI)

4. Open terminal and install OpenCV (Follow Trevor Appleton's excellent guide to verify that OpenCV is installed correctly Install OpenCV on Rpi)

5. Copy the file "Objecttracker.py" to home folder in your rpi either by using scp or by using a flash drive.

# Run the code

1. In your rpi's terminal navigate to folder where you copied "Objecttracker.py"

2. Run the following command:

sudo python bdctc.py

3. Bring a table tennis ball(use a yellow one if possible) in front of your webcam.

5. The ball should be tracked in the window "tracking". 
  If not, adjust the sliders in the windows "HueComp", "SatComp", "ValComp" respectively such 
  that only the region of the table tennis ball appears white in the "closing" window (See the above 
  picture for reference). You may need to experiment a little to get this working. Note down the values of the sliders 
  for which it works for you, you can later edit them in "Objecttracker.py"
