How do you know what size of battery to bring for how long of an operation?  

Below is how I calculate battery need, but I want to stress that this is just a calculation or theory of how long a particular type and size battery "should" last.  You need to test your gear to actually know what it can do, batteries included.

## SOC / DOD

State of Charge and Depth of Discharge are directly related to each other.  An SOC that is 80% means the DOD is 20%, it's that simple.  I prefer to talk in SOC when using the battery and DOD only as it's "cutoff point" where the system will shut down.  

While there are voltage to % charts out there that can give you an idea of the charge state of you battery based on the "unloaded" or "open" voltage, they are not reliable, especially on LifePO4 batteries due to the flatness of the curve for that chemical makeup.  

A Lead-Acid is more linear and thus the voltage to SOC% is better, but your best bet to know how much juice is remaining in a battery is to use a power meter that tracks your Ah usage as you go.

![SOC.png](https://i.postimg.cc/2jB22zwM/SOC.png)

Take note of the voltage on that chart, even at 58v the difference between 40% and 80% DOD is half a volt, no imagine a 12 LifePO4 slope, it's not going to work even if you had a quality meter that can read to the hundredths decimal point. 

I prefer using the [BUDDIPOLE POWERmini 2](https://www.buddipole.com/powermini.html) because it's a charge controller for both LifePO4 and Lead-Acid batteries and pairs with my 30W solar panel for field use, but before getting it I used a simple inline power meter like [This One](https://amzn.to/4hAGswM) to watch loads.  They are cheap and I had two die on me (not that particular model) but if you don't want to spend the $180.00 on the PowerMini2, they will do the trick.

### The Capacity Fallacy
When you purchase a battery, we will use an [8Ah SLAB](https://amzn.to/3XUlmTd) for this example, you would expect to get eight hours of operation at a draw of one amp right?  Wrong!

You can not use a battery to it's full capacity without damaging it and in the case or a Lead-Acid battery you only get 50% of the rated capacity in actual use.  So that 8Ah battery is only going to last 4Ah before the DOD becomes dangerous for the battery.

LifePO4 batteries allow up to 70% DOD before damaging the battery, not only are they lighter but have 20% more usable capacity than a Lead-Acid and thus the growing popularity in HAM radio now that they are becoming more affordable.  It's a buy once cry once situation but they do require their own chargers.

Even if you are just starting out and decide to go all LifePO4, don't forget to have a Lead-Acid charger in your kit as there are a lot more Lead-Acid batteries out there you can use in SHTF than LifePO4 batteries.

## Calculating Current Draw

If you want to estimate how long a battery will last in a given situation, you need to determine the average draw the device is likely to maintain.  If you are sizing for a computer, that draw changes significantly based on the screen (largest draw) is on and how bright you have it set at.  On a radio, you need to know the RX and TX draw and estimate the ratio of them in actual use.

### Example Calc
For example, I know that my Yaesu FT-817 draws 0.32A on RX and 1.97A on TX at 5W using an actual meter, not manufacturer document specs.  If I take those measured values and assume a ratio of 98% RX and 2% TX, I can find the average amp draw and estimated runtime with the following calculations.

#### Average Draw
> (0.32A x .98) + (1.97A x .02) = 0.353A 
#### Battery Usable Current
>8Ah x DOD% = Ah Usable

*Lead-Acid*
	8Ah x .05 = 4Ah

*LifePO4*
	8Ah x .07 = 5.6Ah

#### Runtime Calc
> SLAB: (4Ah / 0.353A = 11.33 hours)  or  LifPO4: (5.6Ah / 0.353A = 15.86 hours) 

### The Case For LifePO4

It becomes clear looking at the calcs above for a 8Ah rated battery that you will get 40% more <u>ACTUAL USE</u> from a LifePO4 battery over a Lead-Acid.  Considering the costs are almost the same in this form factor and size, it's kind of a no-brainer which to go with.

## Test Test Test
In the end, you can get fairly close with calculations but their accuracy is dependent on many variables that you can't really know until you test them out with real time drain tests, so it's best to over estimate than come up short until you have done your due diligence.


