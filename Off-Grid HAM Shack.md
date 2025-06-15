I learned a few years ago the importance of having all my software off-grid and being able to restore my laptop of use any other laptop /  desktop as a digital HAMShack.

>The process is not hard, but you can't get the files off the internet when things go South, so backing up and keeping your backups up to date is critical.  

Running Linux is very easy to do so, but as I've said ([[Windows vs. Linux 1]]), Linux is not a good choice for radio in general and unless you are compiling your own with all the software built in, it's unlikely that you will have all the dependent files available off-grid to reinstall your system or install onto a virgin computer.

I'm a fan of the privacy Linux offers and use [ZORIN OS](https://zorin.com/os/) as my daily driver, but having beat my head on the "Linux HAMShack" before and can still say the "juice is not worth the squeeze".

With Windows 10 being phased out and [offered for free from Microsoft](https://www.microsoft.com/en-us/software-download/windows10ISO), NOW is the time to get a reliable system for HAM radio software to run on that you can restore off-grid if needed.  Just getting the base ISO image is the beginning, collecting additional drivers and the static update for the ISO is also needed.

---
# WINDOWS OS
### WINDOWS-10 ISO
- https://www.microsoft.com/en-us/software-download/windows10ISO
	- This is the last operating system image of Win10 22H2
	- I highly recommend using [Ventoy](https://www.ventoy.net/en/doc_start.html) for installing from a USB.
### WINDOWS-10 OS OFFLINE UPDATE
- https://support.microsoft.com/en-us/topic/windows-10-update-history-8127c2c6-6edf-4fdf-8b9f-0f7be1ef3562
	- I use the - [November 12, 2024—KB5046613 (OS Builds 19044.5131 and 19045.5131)](https://support.microsoft.com/en-us/help/5046613) version as seen in the left column of the page above and have not needed anything more when using my laptop "air-gaped" having never been connected to the internet.
	- EVERY TIME I have allowed my laptop to connect to the internet (~4 times) and update, it has caused issues and an unstable environment.  I only install off-grid now and keep my HAMShack air-gaped now. 
### SURFACE GO 2 SPECIFIC UPDATE
- https://www.microsoft.com/en-us/download/details.aspx?id=101304
	- If you have a Surface Go 2, this update is critical for proper usage and to take advantage of it's unique features.

---
# HAM SOFTWARE
### FLDIGI SUITE 
[http://www.w1hkj.com/](http://www.w1hkj.com/)

Take a look at ([https://sourceforge.net/p/fldigi/wiki/beginners/#what-is-fldigi](https://sourceforge.net/p/fldigi/wiki/beginners/#what-is-fldigi)) to better understand the program and digital modes in general. Be sure to download all documentation for each program also. Below are the programs you will want.

- FLDigi Suite
    - fldigi/flarq
	    - While I have used FLDigi for decoding CW and using Contestia / MSK for AmRRON exercises, I have little use for it or any other program that can not be used unattended for my "Emcomms" software.
    - flrig
        - I use the CAT control on FLRig because it allows several programs to run at the same time without fighting over who has control of the rig. FLRig controls the rig, as the name implies, and JS8Call, VaraAC, FLDigi look to it to send commands to the rig. 
    - flmsg
    - flamp

### JS8CALL
[http://files.js8call.com/latest.html](http://files.js8call.com/latest.html)

- JS8Call
    - I feel this is the best weak signal program out there as it allows messages to be left and retrieved later on when the use can get time to do it.  It allows leaving messages on other peoples radios for later retrieval.  It’s strength is the ability to get through jamming and poor propagation. I’ve had my 5 watt station decoded at -31db, the advertised number is around -24db as the best to expect.  Updates are very slow but seem SOLID when they are released.

### JS8SPOTTER
[https://kf7mix.com/js8spotter.html](https://kf7mix.com/js8spotter.html)

- JS8Spotter
    - A helper program for JS8Call that greatly enhances your ability to transfer information while your station is unattended. Meaning you don’t have to sit at your computer listening for information, you can have this program running in the background “scarfing up” information based off key words, call-signs, and JS8Call groups.  It allows you to see traffic between group members (call to call) that you might be interested in.

### VARA
[https://rosmodem.wordpress.com/](https://rosmodem.wordpress.com/)

- Vara
    - Vara is a mode, not a program. You can use it with several programs like Winlink or VaraAC. Download VaraHF at a minimum, but I would grab all the programs on that page for posterity sake.
    - I also recommend spending the $69 for the high speed unlock as it speeds up Winlink times and is auto adjusting to the prop conditions.  One time payment off-grid code.

### VARAC
[https://www.varac-hamradio.com/](https://www.varac-hamradio.com/)

- VarAC
    - A very good text based program that works “weak signals” almost as well as JS8Call but at exponentially higher speeds, it also uses a wider bandwidth 500 kb/m for the unpaid version of VARA and 2300 if you have bought the VARA license.
    - VarAC is free and a software package that uses the Vara mode, it does not have it's own transmission mode but rides as a layer on top of Vara.

### BKTIMESYNC
[https://www.maniaradio.it/en/bkttimesync.html](https://www.maniaradio.it/en/bkttimesync.html)

- JS8Call requires time synchronization and being as we have an OFF-GRID system, that means we need software to talk to our GPS dongle or learn how to correct our PC clocks in some other way. My preferred way of keeping time off-grid is described in my [[GPS Time Syncing]] post.  It’s amazing how often the PC will get off in time, many times after only a weeks worth of time without a correction being made.

### HAM DRIVERS
- DigiRig Drivers ([CP210x Universal Windows Driver](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads)    
- CHIRP Drivers ([PL2303 Windows Driver Download   USB to UART RS232 Serial](https://www.prolific.com.tw/US/ShowProduct.aspx?p_id=225&pcid=41))
- FTDI Comm Drivers ([https://ftdichip.com/drivers/d2xx-drivers/](https://ftdichip.com/drivers/d2xx-drivers/))
- Misc System Drivers (collected over time and stored on my Proton Drive)
    - ([https://drive.proton.me/urls/KFK8EYYPYM#DdzhMfaPB8qN](https://drive.proton.me/urls/KFK8EYYPYM#DdzhMfaPB8qN))


### FILE SYNC APP
- [https://freefilesync.org/](https://freefilesync.org/)
	- A free piece of software used for incremental updates and creating a clone of your USB, two is one, one is none!

---
This is the end of pt.1, collecting the programs.  In the near future I hope to add to this post how to use Ventoy for setting up a new laptop HAMShack using a USB with the Win10 ISO on it and another USB with the rest of the programs/files listed above.

To be continued...
