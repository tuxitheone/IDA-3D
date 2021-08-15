# IDA 3D seminar
	I dette webinar vil vi forsøge at give jer en større forståelse for, hvad 3d print er? hvorfor vi gøre det?
	Vi vil forklare lidt om FFF (Fused filament fabrication) SLA/DLP (stereolithography apparatus)
	
# Software
[CituBox](https://www.chitubox.com/en/download/chitubox-free)<br>
[Cura 4.8.0](https://github.com/Ultimaker/Cura/releases/tag/4.8.0)<br>
	
# Nice to know Links
[Filament Properties Table](https://www.simplify3d.com/support/materials-guide/properties-table/)<br>
[3D Printer Filament Guide](https://www.3dmakerengineering.com/blogs/3d-printing/3d-printer-filament-guide)<br>
	
# Filament Shop
[3D Printed - Auning](https://www.3dprinted.dk/)<br>
[3D Experten - Nørresundby](https://3deksperten.dk/)<br>
[3D Store.dk - Herning](https://3dstore.dk/)<br>
[Filament.nu - Vejle](https://filament.nu/da/)<br>
[Solunoid - Aabenraa](https://www.solunoid.dk/)<br>

# OctoScreen LCD touch 7"
https://github.com/Z-Bolt/OctoScreen <br>
https://www.youtube.com/watch?v=OdAG-KU5aOg <br>
	Screen flassing
		sudo nano /etc/rc.local
			scrolled all the way down in this list and before the last exit 0
		Indset:
		systemctl start octoscreen
			pressed control X, then Y then Enter to save
		sudo reboot

This might be enough to fix the problem, but in my case it was not, but after doing this i reinstalled
by pasting in following:

		sudo apt-get install libgtk-3-0 xserver-xorg xinit x11-xserver-utils

Then after running that i pasted in:

		wget https://github.com/Z-Bolt/OctoScreen/releases/download/v2.5.1/octoscreen_2.5-1_armhf.deb
		sudo dpkg -i octoscreen_2.5-1_armhf.deb
		sudo reboot

Now OctoScreen works, hope this is help for anyone else here.

# OctoPrint
	Plugin
		https://github.com/vitormhenrique/OctoPrint-Enclosure
		https://github.com/kantlivelong/OctoPrint-PSUControl
		