This is an expect script to operate the IP9258 network power switch from the command line over telnet.

Script can be called to check status, power everything up, power everything down, turn on a commonly used set of devices or set your own custom configuration using 4 0s and 1s.
	
	Usage: power up|down|check|usual|xxxx

The script requires activating telnet in the setup of the device and setting your IP address and password in the script. This script is written in expect, so expect must also be installed and you should update the first line to the correct path for your system.

Additional information about the device is available at http://www.aviosys.com/9258st.html.

I have no affiliation with the company, I just wanted to be able to operate the device more easily.
