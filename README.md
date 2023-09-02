# PDL_Sala_project
### PDL project - OFET analysis

This script is meant to act as a low-effort tool to handle data regarding (Organic) Field Effect Transistors.<br>
The only input from the user required is a directory; then, through a loop, the script scans each file in that directory containing the raw data of the electrical characterisation of the devices, saving plots automatically and generating a summary dataframe of useful parameters from each file.<br>
Generated figures regard transfer curves (currents against gate voltage), field effect mobility curves (against gate voltage), threshold voltage extraction. The dataframe also includes on-current/off-current ratios as well as mean switched-on mobilities. <br><br>
It's a fairly agile, low memory-demanding script, and through Google Drive and Colab, it can be accessed potentially from any computer (regardless of specifications and installed softwares) to perform a quick data analysis of devices fabricated according to several different conditions. Based on these premises, this script is not meant to calculate all the possible parameters related to OFETs, it only deals with the most informative values and plots, that I need on a regular basis.<br><br>
The here attached Transfer files are different for semiconductor type, device geometry and insulating layer, and they can be used to test the script's capability to loop on multiple files and adapt to different devices. <br>
In order for the script to work, those two files should be in the same folder, whose path will be inserted into the code.
