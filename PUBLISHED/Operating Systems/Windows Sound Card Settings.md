### DigiRig Sound Card Setup
Setting up the Windows side of the house is pretty important when using the DigiRig and other external sound cards with JS8Call and VarAC in my experience, specifically the step of assigning the USB sound card to the APPS under Advanced Sound options.

Renaming the USB Input / Output to DigiRig INPUT / DigiRig OUTPUT leaves no doubt and I recommend this setup be done before opening JS8Call or VarAC.

---
### Setup Steps
#### Output
1. Open Sound Settings
2. Open USB Audio Device OUTPUT
3. Rename to DigiRig OUTPUT
4. Set level to 50%
5. Disable all enhancements.
#### Input
1. Open USB Audio Device INPUT
2. Set volume to 50% 
3. "Listen to this device" = un-checked
4. AGC (Automatic Gain Control) = un-checked

#### App Volume and device prefs
1. Hard assign DigiRig INPUT / OUTPUT to each software after it is started.
2. Hard assign in the software itself, ==do not use DEFAULT== in either place.

---
### Step By Step Pictorial
Below is a pictorial of my setup with JS8Call and VarAC as the software example on the (tr)uSDX radio.  

I prefer to set the windows INPUT/OUTPUT at 50% and make adjustments in the individual software settings as I have not found them to be linear in use, meaning you will need to fine tune in the programs no matter what the Windows levels are set to.  

Fifty-percent (50%) output in Windows allows enough volume to drive the external sound card on it's own without over driving it and the radio.  You can then adjust the output up in the software to reach 1/3 ALC on your radio to produce a clean but strong signal.

![soundcard.png](https://i.postimg.cc/CMXRVBRm/soundcard.png)
To get started, ==Right click== on the speaker in the tray, select "==Open Sound Settings==".

#### Output
![1soundcard.png](https://i.postimg.cc/SN0DxGRP/1soundcard.png)
Here you see my DigiRig USB Audio Device is already renamed to DigiRig OUTPUT which is done on the next step by clicking on "==Device Properties==".

![2soundcard.png](https://i.postimg.cc/hPSQsJ5j/2soundcard.png)
Change the name of your USB device, then click "==Advanced device properties==" in the far right of the screen.

![3soundcard.png](https://i.postimg.cc/vBN2hFQ8/3soundcard.png)
You can change the icon of the device here if you like, I don't bother.

![4soundcard.png](https://i.postimg.cc/HkTGVmnF/4soundcard.png)
Set levels to 50%.

![5soundcard.png](https://i.postimg.cc/6qKcY9kX/5soundcard.png)
Disable all enhancements.

#### Input
![6soundcard.png](https://i.postimg.cc/tgtYFpNP/6soundcard.png)
Under Input, select "==Device properties==".

![7soundcard.png](https://i.postimg.cc/Y0crPPRk/7soundcard.png)
Set volume to 50% and select "==Additional device properties==" in top right corner.

![8soundcard.png](https://i.postimg.cc/GmtWkQPj/8soundcard.png)
Make sure "==Listen to this device==" is ==un-check== unless you radio can not output to it's speaker and audio out at same time, like the (tr)uSDX.

![9soundcard.png](https://i.postimg.cc/528wkcm9/9soundcard.png)
AGC (Automatic Gain Control) should ''==ALWAYS be left off==" so it is not fighting your radio software. This is one of those settings Windows will change back on an update, be sure to check it if you ever re-connect to the internet.

![10soundcard.png](https://i.postimg.cc/2SYwY8yL/10soundcard.png)
Select "==App volume and device preferences==" at bottom of page.

![11soundcard.png](https://i.postimg.cc/hjX8sXy6/11soundcard.png)
When you have no software running and the DigiRig is plugged in, this is what you see.

![12soundcard.png](https://i.postimg.cc/sxphH7p6/12soundcard.png)
Change the DigiRig INPUT to point to the DigiRig USB device.

![13soundcard.png](https://i.postimg.cc/zGPVj0sD/13soundcard.png)


![14soundcard.png](https://i.postimg.cc/7L0w29DW/14soundcard.png)
The master volume on this page is indication and linked to the volume control in your system tray, it's not important to set here as much as it is to ==keep the DigiRig OUTPUT at 50%== in the slider shown in the lower corner.

![15soundcard.png](https://i.postimg.cc/wvqZjQBJ/15soundcard.png)
You can see how it switched when selecting the onboard speakers.

![16soundcard.png](https://i.postimg.cc/qMxmzC9x/16soundcard.png)
Once you start up JS8Call or other software you intend to use your DigiRig with, they will appear in this settings page, "==hard assign==" them here and in the HAM Software also as shown below.

![17soundcard.png](https://i.postimg.cc/nc3vyKyg/17soundcard.png)
Sometimes JS8Call does not "see" your audio device as you renamed it.  I usually reboot after assigning it in "Sound Settings" which seems to work.

![18soundcard.png](https://i.postimg.cc/XXMwVFSF/18soundcard.png)
Settings for the (tr)uSDX in VarAC, be sure to use "==Left Channel==" ONLY on this radio as well as "==RA-Board-1==" for PTT.  This is displayed above, but the setting is under Vara Setup as a checkbox.
### Double Checking Your Setup
![19ssoundcard.png](https://i.postimg.cc/cLqHdnXx/19ssoundcard.png)
When you are done your should see the DigiRig as the "Default ==Communications== Device" and the laptop speakers as the "Default Device", if it is not, ==right click== and set it to that.

![20ssoundcard.png](https://i.postimg.cc/K8J8BHmz/20ssoundcard.png)
You can get to the same place by going through the Control Panel.

See the [Settings file for the (tr)uSDX](\(tr\)uSDX.md) for greater details.

Simple procedure but very important one than many new operators miss.  Keep an eye on your settings, especially if you are NOT running your Windows OS Air-Gapped.

---
### Change Log
	0.1 [02.22.25] Added double checking your setup
	0.0 [02.20.25] Initial Posting


