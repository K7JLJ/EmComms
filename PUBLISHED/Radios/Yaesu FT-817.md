The FT-817 was my first HF radio and one I would not sell.  It's the "weaker  finals" model (non-ND) but has worked like a champ for me for over 10 years now.  I picked it up with a bunch of batteries for $400.00 of eBay and could not be happier with it's performance.

It was a bit disappointing trying to do 80M voice at 5W, but it taught me to improve my antenna and eventually to go to JS8Call to make the most of the power I had.  With a resonant dipole in NVIS I was able to start making those check-ins on a regular basis.

With JS8Call I was able to easily talk across the nation on 40M, it's a solid performer on 40M now that the solar cycle is peaking again.  It was rough starting my HAM "career" in the 11 year low in 2014, but we learn from struggling and mistakes, not buying a 1500W amp and heating the ionosphere.

## Digital Mode Parameters

| #   | MENU      | FUNTION                                                                                                                                       | AVAILABLE VALUES                           | DEFAULT | ==DigiRig== |
| --- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | ------- | ----------- |
| 14  | CAT RATE  | Set the transceiver's circuitry for the CAT baud rate                                                                                         | 4800/9600/38400 bps                        | 4800    | 38400       |
| 24  | DIG DISP  | Define the displayed frequency offset<br>during DIG (USER-L or USER-U) mode operation                                                         | -3000 ~ +3000 Hz                           | 0 Hz    | 0 Hz        |
| 25  | DIG MIC   | Adjust the audio input level from terminal equipment<br>(such as a TNC or PSK-31 sound card)<br>during DIG (Digital) mode operation           | 0 ~ 100                                    | 50      | 50          |
| 26  | DIG MODE  | Select the mode and sideband (if applicable)<br>in the DIG (Digital) mode                                                                     | RTTY/<br>PSK31-L/PSK31-U/<br>USER-L/USER-U | RTTY    | USER-U      |
| 27  | DIG SHIFT | Define the carrier frequency offset<br>during DIG (USER-L or USER-U) mode operation<br>Enable Tx/Rx operation on the Alaska Emergency Channel | -3000 ~ +3000 Hz                           | 0 Hz    | 0 Hz        |
| 49  | TOT TIME  | Select the Automatic Power Off time<br>(time before power goes off)                                                                           | OFF/1 ~ 20 min                             | OFF     | 3 min       |
|     |           |                                                                                                                                               |                                            |         |             |

### Adjusting For Minimum ALC 
Since there is no way to watch the ALC the FT-817 while adjusting the MENU 25 DIG MIC levels, you need to adjust your output to the point that you are reaching peak output power, but not over-driving your signal to the point of splatter and/or harmonics.  

Once you have performed the procedure below, you can double check by adjusting the output slider in JS8Call and watching AL on the screen until you have between 0-1 bars ALC.  

You will see the output power in your analog meter max at this point and drop from max power when the ALC (shows on screen as AL) reads below zero bars.  Since you can't see negative bars, keeping it at 1-2 seems to be the sweet spot.  With an external SWR meter, I leave the screen on AL and watch for over driving so I can adjust with the software output slider.  

>Press the [B] button to cycle through (Power, ALC, SWR, or MOD indication).

For me the key is setting [Win10 Sound Card Settings](Win10%20Sound%20Card%20Settings.md) to 50% on the output to the external sound card (DigiRig) and then adjusting MENU 25 DIG MIC up to max power with JS8Call's output set to ~ 50%, this dials in my main program while also giving the largest amount of span for other programs to use.  

>By finding a middle ground you are giving more UP/DN range for other programs.

![JS8Call_slider_Sound_817.jpg](https://i.postimg.cc/s2C6qTZc/JS8-Call-slider-Sound-817.jpg)

![JS8Call_LOW_Sound_817.jpg](https://i.postimg.cc/G2qXBrg7/JS8-Call-LOW-Sound-817.jpg)

With the OUTPUT slider for JS8Call at ~50%, transmit a tone from the software then adjust the dial on MENU 25 to a point that the rig is outputting less than it should be (34% = ~2W below), then adjust up until the power output on an external power  meter ([MFJ-491E](https://i.postimg.cc/HsNqL0fG/s-l960.png) in my case) peaks out at the known output of the radio, 5W in the case of the FT-817.

Bring MENU 25 up until you see deflection on the meter stop, then confirm by lowering MENU 25 down until you get needle movement then again, slowing back up to where it stops moving.  For my rig, that is about 50 but your settings will likely be different.

![JS8Call_HIGH_Sound_817.jpg](https://i.postimg.cc/L5WvTDpj/JS8-Call-HIGH-Sound-817.jpg)

After you have adjusted your FT-817 to your primary piece of software, you can use the output sliders in other software programs to test for max deflection on the meter.

Example: Setting the Output in VarAC
![VarAC_Sound_817.jpg](https://i.postimg.cc/TPx0ChZN/Var-AC-Sound-817.jpg)  


## Radio RX / TX Levels

Using the [BUDDIPOLE POWERmini 2](https://www.buddipole.com/powermini.html).

### RX Only = 0.32A
- 0.29A  with the lamp OFF
![FT817_RX_AMPS.jpg](https://i.postimg.cc/kXQf4xV5/FT817-RX-AMPS.jpg)
### TX @ 5W = 1.97A
![FT817_5W_AMPS.jpg](https://i.postimg.cc/jd741y6X/FT817-5-W-AMPS.jpg)


## Intermediate Battery Use

The FT-817 is my primary rig for SHTF because it is small and stout.  This radio has been around since 2001 (mine is an original 817 before the ND) and I've had my eBay find for 10 years now and it keeps on ticking.  The 0.32A draw at rest is with the back-light in on as I figure that's how I'm going to operate it, even so it's 1/3 the RX draw of it's big brother the [Yaesu FT-891](Yaesu%20FT-891.md) and is fully functional with all the digital modes I use.  

Like my [Yaesu FT-891](Yaesu%20FT-891.md) I can simultaneously run JS8Call, VarAC, and FLDigi and I know it can handle the duty cycles over time that digital modes demand, unlike my [(tr)uSDX](\(tr\)uSDX.md) which while much easier on the batteries is not as capable and I reserve it for a field emergency radio only when the FT-817 is forced into the role of my base radio.  Otherwise I'm going to depend on something more stout than the [(tr)uSDX](\(tr\)uSDX.md) which broke while I was writing this.

Just sitting in RX mode it will burn just under 1/3 of an amp every hour, that means a 7Ah SLAB will be dead in ~10.5 hours without transmitting once.

I love my FT-891 as a base or vehicle setup, and I can feed it with the generator / solar setup at home for most of the year,  but it's not the tool for SHTF when the grid is down for months.  I'm going to be using my FT-817 in that scenario to save power.

### Real Life Drain Test

#### Test #1
I put the FT-817 on air at 03.01.25 - 1745 and let it run the 2P (7.5Ah) battery setup I was  using to just over it's "drop out voltage" of 10.8 by 03.02.25 - 1750. 

My use estimation for JS8Call when not on a calling freq and with HB off is 97%RX / 3%TX.

> (0.32A x .97 = .31A) + (1.97A x .03 = .06A) = 0.37A per hour = 0.37Ah
> 7.5Ah + 7.5Ah x 50%DoD = 7.5Ah / 0.37Ah = 20.27 estimated hours of operation

Actual run time (stopped before cut-off voltage) was 24 hours and 5 minutes, which means my ratio was either a little higher on TX, the batteries are not fully charging, or who knows.  It's an estimation, what matters is that you test your actual run times and not venture out hoping to get what your estimations are showing you.  

In this case it was pretty ball park, YMMV.  Test, test, test.

#### Test #2
Same scenario this time using the $24.00 [Talentcell Rechargeable 12V 3000mAh Lithium ion Battery Pack](https://amzn.to/4hygbiI) 

> (0.32A x .97 = .31A) + (1.97A x .03 = .06A) = 0.37A per hour = 0.37Ah
> 3Ah + 70%DoD = 2.1Ah / 0.37Ah = 5.68 estimated hours of operation

Actual run time (found dead between checks) was approx. 6.5 hours, again my estimation TX cycle was higher than experienced.


---
## Change Log
	0.2 [03.13.25] - Added Run Test With Tallentcell Battery 
	0.1 [03.02.25] - Added Initial Settings & Adjusting For Minimum ALC 
	0.0 [03.01.25] Initial Posting
