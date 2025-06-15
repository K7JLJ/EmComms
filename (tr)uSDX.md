# F/W v2.00x Settings 
These are my particular radios settings, yours might be off a little in comparison, but these settings have worked well for sometime now. 
## MENU 1 
	.1 Volume = 6
	.2 Mode = USB
	.3 Filter BW = 4k0
	.4 Band = 40m
	.5 Tune Rate = 1k
	.6 VFO Mode = A
	.7 RIT = OFF
	.8 AGC = ON
	.9 NR = 0
	.12 S-meter = S
	.13 SWR Meter = FWD-SWR
## MENU 2
	.4 Semi QSK = ON
	.5 Keyer Speed = 12
	.6 Keyer Mode = Straight
	.7 Keyer Swap = ON
## MENU 3
	.1 VOX = OFF
	.2 Noise Gate = 4
	.3 TX Drive = 4
	.4 TX Delay = 0
## MENU 4
	.1 CQ Interval = 5
	.2 CQ Msg1 = CQCQCQ K7JLJ
	.3 - .7 CQ Msg2 - Msg6
## MENU 8
	.2 PA Bias = 128
	.3 Ref freq = 26997800 (unique to radio)
	.6 R Shunts = 18
	.7 LPF Config = Lo
## MENU 9
	.7 F/W = 2.00x


# Mighty But Fragile
## "And... it's broke!"
While I was comparing RX / TX draws for my radios Yaesu FT-891, Yaesu FT-817, and (tr)uSDX) just pulling it out of it's padded Apache box put enough tension on the BDC connector to break the soldier points off the circuit board.  I have not opened it to see if it can be repaired but suspect it can,and will be adding a guard around this design flaw.

![truSDX_BNC.jpg](https://i.postimg.cc/ZK9zMYqm/tru-SDX-BNC.jpg)

This has caused me to reconsider it as a SHTF field radio over my Yaesu FT-817 and I am placing it into the Contingent category of my PACE plan.


## "And.... it's Fixed!"
So I took the the circuit board to work where I have access to a [REAL soldering setup](https://amzn.to/41rtV9f) that can poor the coals to it at 700F.  I could not even start to melt it with my USB iron or Harbor Freight special.  If I eve leave this job and loose access to the soldering setup, I will be purchasing this [Weller 70 Watt Digital Soldering Station](https://amzn.to/43kzrNt) immediately!  Sometimes you just need the right tool.  I'm sure I could have gotten it field repaired with my [$19 Cordless Soldering Iron](https://amzn.to/3F4OBw4) but it would have been nasty for sure.

![truSDX_BNC_Backtrace.jpg](https://i.postimg.cc/4xJcDHQr/tru-SDX-BNC-Backtrace.jpg)

The back side of the SMA connection, ground pin connections.

![truSDX_BNC_Fronttrace.jpg](https://i.postimg.cc/Jh0knwgx/tru-SDX-BNC-Fronttrace.jpg)

The front side with the center wire and two more ground connections.

![truSDX_BNC_position.jpg](https://i.postimg.cc/Kvb3T3wR/tru-SDX-BNC-position.jpg)

And a pre-fit position check before removing the O-ring and HD flat-washer I was using as a base support for the BNC.  

> This is what caused the breakage. I was tightening the BNC down against the radio and using an O-ring to hold tension on it.  OBVIOUSLY too much tension as a little bump pulled the soldier joint right off the board!

After soldering it back on, I kept the washer under the BNC for support but removed the O-ring and added some blue lock-tight to the SMA/BNC threads.

![truSDX_BNC_fixed.jpg](https://i.postimg.cc/wTkyQTYF/tru-SDX-BNC-fixed.jpg)

The moment of truth was hitting the CW button and I got full output at 1:1 SNR for 10 seconds, so I'm calling it fixed.

# Run Tests

## (3x 18650 Batt Pack)
One of the best features of the (tr)uSDX is that it runs on very little power and the accessory battery pack I have (3 x 18650) is all you need to keep it up and running for days, even 24/7.

Transmitting at 4-5W on 40M it ran for almost 34 hours without issue.  On the first set of batteries I replaced them sooner than needed because KG7YSX said he was seeing harmonics from my signal on his waterfall.  Turns out it was just weird propagation conditions as other signals on 7078 were doing it also.

The second set I ran to a very low and to damaging levels to see if I could still transmit.  It was putting out 1w even at ~5v, which is plenty on JS8Call to make connections.  From this short test I would estimate working times of 30 hours on one set of batteries, allowing plenty of time to charge the replacement set from my portable solar setup.

My next test will be using the Talentcell LifePO4 cell instead.

| Date | Time  | Voltage | Watts Out | Elapsed Time     |
| ---- | ----- | ------- | --------- | ---------------- |
| 4/13 | 18:10 | 11.9    | 5.5       |                  |
| 4/14 | 04:00 | 11.4    | 4.4       | 9hr, 50min       |
| 4/14 | 17:40 | 10.8    | 4.6       | 23hr, 30min      |
| 4/15 | 04:01 | 10.3    | 4.4       | 1day, 9hr, 51min |
|      |       | NEW     | BATTS     |                  |
| 4/15 | 18:16 | 11.4    | 5.3       |                  |
| 4/16 | 19:40 | 10.3    | 4.3       | 1day, 1hr, 24min |
| 4/17 | 04:03 | 9.9     | 4.1       | 1day, 9hr, 47min |
| 4/17 | 18:23 | 5.3     | 1         | 2day, 7min       |


