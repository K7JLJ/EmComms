## Digital Mode Parameters

Below are the changed parameters on my FT-891 running a [Digirig DR-891](https://amzn.to/4h7a30T) external sound card and [LDG AT-100ProII](https://amzn.to/4hY1Xst) auto tuner.

| MENU     | #         | ITEM           | AVAILABLE VALUES                     | DEFAULT | ==DigiRig== |
| -------- | --------- | -------------- | ------------------------------------ | ------- | ----------- |
| DISPLAY  | **02-02** | DIMMER BACKLIT | 1 - 15                               | 8       | 3           |
| DISPLAY  | **02-03** | DIMMER LCD     | 1 - 15                               | 8       | 3           |
|          |           |                |                                      |         |             |
| GENERAL  | **05-03** | NB LEVEL       | 0 - 10                               | 5       | 0           |
| GENERAL  | **05-04** | BEEP LEVEL     | 0 - 100                              | 30      | 4           |
|          |           |                |                                      |         |             |
| GENERAL  | **05-06** | CAT RATE       | 4800 \| 9600 \| 19200 \| 38400 (bps) | 4800bps | 38400bps    |
| GENERAL  | **05-07** | CAT TOT        | 10 \| 100 \| 1000 \| 3000 (msec)     | 10msec  | 100msec     |
| GENERAL  | **05-08** | CAT RTS        | ENABLE \| DISABLE                    | ENABLE  | DISABLE     |
|          |           |                |                                      |         |             |
| GENERAL  | **05-14** | TX TOT         | OFF \| 1 - 30 (min)                  | OFF     | 3 Min       |
|          |           |                |                                      |         |             |
| MODE-DAT | **08-01** | DATA MODE      | PSK \| OTHERS                        | PSK     | OTHERS      |
| MODE-DAT | **08-02** | PSK TONE       | 1000 \| 1500 \| 2000 (Hz)            | 1000Hz  | 1500Hz      |
| MODE-DAT | **08-03** | OTHER DISP     | -3000 - 0 - 3000 (Hz)                | 0Hz     | 1500Hz      |
| MODE-DAT | **08-04** | OTHER SHIFT    | -3000 - 0 - 3000 (Hz)                | 0Hz     | 1500Hz      |
|          |           |                |                                      |         |             |
| MODE RTY | **10-01** | RTTY LCUT FREQ | OFF \| 100 - 1000 Hz                 | 300Hz   | 1000Hz      |
|          |           |                |                                      |         |             |
| MODE SSB | **11-07** | SSB BFO        | USB \| LSB \| AUTO                   | AUTO    | LSB         |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-01** | HF SSB PWR     | 5 - 100                              | 100     | 80          |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-03** | HF PWR         | 5 - 100                              | 100     | 30          |
| TX GNRL  | **16-04** | 50M SSB PWR    | 5 - 100                              | 100     | 10          |
| TX GNRL  | **16-05** | 50M AM PWR     | 5 - 40                               | 25      | 10          |
| TX GNRL  | **16-06** | 50M PWR        | 5 - 100                              | 100     | 10          |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-10** | DATA MIC GAIN  | 0 - 100                              | 50      | 35          |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-15** | TUNER SELECT   | OFF \| EXTERNAL \| ATAS \| LAMP      | OFF     | EXTERNAL    |
| TX GNRL  | **16-16** | VOX SELECT     | MIC \| DATA                          | MIC     | DATA        |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-20** | DATA VOX GAIN  | 0 - 100                              | 50      | 10          |
|          |           |                |                                      |         |             |
| TX GNRL  | **16-21** | DATA VOX DELAY | 30 - 3000 (msec)                     | 100msec | 100msec     |
| TX GNRL  | **16-22** | ANTI DVOX GAIN | 0 - 100                              | 0       | 10          |

### Parameter Spreadsheet
Below is a link to an awesome spreadsheet someone made with ALL parameters on my ProtonDrive. https://drive.proton.me/urls/FXQ86CC98M#2nLyNGhAVhh8


## Enhancing RX Demo
![](https://youtu.be/2I3TnK-La6I&Rel=0)


## Radio RX / TX Levels

If you don't have a [BUDDIPOLE POWERmini 2](https://www.buddipole.com/powermini.html) yet, you should really do yourself a favor and get one.  For field use and solar charging a cell it's the only way to really know how much operating time you have. SOC is too unreliable, especially with LiFePO4 batteries.
#### RX Only = 0.95A
![FT891_RX_AMPS.jpg](https://i.postimg.cc/05wDKRfc/FT891-RX-AMPS.jpg)
#### TX @ 5W = 5.03A
![FT891_5W_AMPS.jpg](https://i.postimg.cc/4NcYFfc9/FT891-5-W-AMPS.jpg)
#### TX @ 30W = 7.57
![FT891_30W_AMPS.jpg](https://i.postimg.cc/0Ny7zzWw/FT891-30-W-AMPS.jpg)


## A Battery Hog

The FT-891 is never going to be a good choice for prolonged outages unless you have a solar setup to handle it's nearly 1 amp RX level. Just sitting on no volume listening will burn just under 1 amp of battery power every hour, that means a 7Ah SLAB will be dead in ~3.5 hours without transmitting once.

I love my FT-891 as a base or vehicle setup, and I can feed it with the generator / solar setup at home for most of the year,  but it's not the tool for SHTF when the grid is down for months.  I'm going to be using my FT-817 or (tr)uSDX in that scenario to save power.

---
## Change Log
	0.0 [03.01.25] Initial Posting
