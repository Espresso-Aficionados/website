---
layout: default
title: Espresso Profiling
parent: Guides
nav_order: 3
---

# What is Profiling
A reasonable definition of profiling is: 'The act of consciously gathering data on metrics during an espresso extraction or recording a profile.' Because the colloquial definition appears to be more about following a profile, i.e., 'Adjusting the flow, pressure, or temperature in a shot to manipulate the extraction and produce a different result,' I'll use the term profiling to mean 'following a profile.' There are a number of different ways to accomplish this, depending on available equipment. My preferred use case for profiling is modulating the evenness of my extraction to achieve a desired taste profile.

## Some quick definitions
* Water Debit

   In a pump machine, the amount of water that comes out of the group without restriction from coffee or a basket. Commonly expressed as (X)ml/s. Variable in flow profiling systems.

* Channeling

   When water flows through coffee it tries to find the path of least resistance. Channeling is a phenomenon that occurs when the path of least resistance allows the water to form a hole in the puck. This allows the water to flow primarily through one spot, reducing overall extraction and simultaneously contributing negative overextraction flavors to the final beverage. Bitterness, astringency, and sourness all together indicate severe channeling. Unavoidable entirely, but this can be reduced to the minimum without a ton of effort.

## Fixed Profiles
Every machine you have ever used has a profile of some sort. The least flexible profiles are those that are controlled by a pump and push out a fixed rate of water with no overpressure valve. We go through various changes to the system to get more complex pump machines that do a slightly better job, but the focus of this section is on adjustable profiling systems.

This section is here because it is important to understand that ANY system can be modified based on the below principles to produce excellent coffee. Some may be too instable or expensive to modify, but many machines have been modified in a simple manner to adjust preinfusion, max pressure, or other parameters.

## Adjustable Profiles
There are now a number of machines and mods that allow on the fly control for the end user. These adjustable profilers have one primary benefit worth considering; they decouple the relationship between grind size and flow rate to a certain degree. This allows us to make espresso beverages with really finely or coarsely ground coffees. The effective result is that we can boost extraction, clarity, or strength along with some other taste parameters.

### Flow Control
Most control interfaces are really controlling flow. I find it easier to think about espresso dialing through flow rates and not pressure levels, but that's because my primary machine has a needle valve that pretty directly controls the free flow rate of water. The actual flow rate during extraction is a function of the pressure at the puck and the input flow rate; if there is more flow than the puck can allow through at ambient pressure, pressure builds up. As an example, you can deal with a choked shot (one that isn't flowing at the desired output rate) by reducing flow, which subsequently reduces pressure and allows the puck to relax. After the shot starts flowing again the puck dyanmics have changed and more flow can be added without the shot choking again.

### Pressure Control
Some machines either directly or indirectly control pressure instead of flow. A good example is the La Marzocco GS3 MP which uses a conical valve to shunt excess flow once the desired pressure is reached. Translating flow profiles into pressure profiles is possible using either charts from a decent or watching extractions that show a pressure gauge on something like a bianca.

### Computer Control
There are a few complex computer based control systems that can generally use a flow or pressure model to adjust extraction profiles. The most advanced is the decent espresso machine, but there are several other machines that can also make very repeatable espresso.

### Levers
Direct and spring levers make excellent profiling machines. Direct levers work very much like a better version of pressure profilers, though most of them have varying degrees of challenge when you're trying to control temperature. There are a few that are inherently stable, but the others require a lot of care and attention. Spring levers have a relatively fixed profile, but the lever can be assisted or resisted to make modifications to the flow rate of water through the puck. Certain lever designs are going to have a relatively low max pressure in the preinfusion phase, so do keep this in mind.

# How to Profile

## What is extraction? How about TDS?
Extraction is the percentage of soluble mass that left your coffee puck and ended up in the beverage. Total Dissolved Solids (TDS) is the percentage of the final beverage that is made up of dissolved coffee solids and not water.

Here's a simple example. If you have a 20g puck and a 10% TDS from a 1:2 ratio, you have moved 4 grams of coffee into the cup and therefore extracted 20% of the mass. How do I know this? The equation for estimating extraction from the ratio and TDS is 
`EY = (brewed coffee weight * TDS) / (dry grounds weight)`

## Setting Recipes
In general an espresso recipe is TDS% at a given EY%. If you're looking for a 10% TDS and think the coffee needs 20% EY, you can only achieve this at a 1:2 ratio. You probably don't have a way to measure this, and that's just fine.

My typical method for picking a recipe is to use the highest reasonable ratio I can and then I push extraction up to the astringency ceiling. If I taste astringency, I typically try to improve the evenness of my extraction and see if it is still there. If I can't eliminate it, I know I need to make a change. Also, if I want more strength or flavor intensity, I'll make a change.

There are better resources than this guide for figuring out the basics of dialing, just try to remember that strength and extraction can be dialed where you like them. 1:2 in 30s is not a rule to be strictly adhered to.

## Calibration
Needle valve based profilers require you to understand your actual water debit. This gets a little fuzzy for vibration pump machines, but for rotary pump units you can measure the output of several fixed needle positions over 10 seconds to figure out your ml/s. Just use a scale and divide the grams by 10. For vibe pumps it may make sense to do the same thing over your expected preinfusion length so you know about how much water would come out in that time.

## Components of a profile

The first thing that happens in any profile is that the coffee gets wet before pressure starts to build. Depending on the machine, this can be very fast or very slow. Our goal is to maintain puck integrity, so there is probably a reasonable balance between high and low speeds. I tend to fill fast (8ml/s) but that isn't for everyone.

### Preinfusion
I don't love this name so I'm replacing it in this guide. The next two phases (fill and soak) replace preinfusion in my written work. One potential method for improving espresso preparation is to get the coffee evenly wet as quickly as possible and to soften the puck to the proper degree so water can flow through at our desired flow rate. There are many methods for doing this, but understanding that we're setting up the next phase is what I consider to be most important here.

#### Fill
Defined as the time it takes to fill the headspace above the puck and build initial pressure.

#### Soak
Defined as the time where pressure is either held or flow is shut completely off to allow pressure to drop before the main percolation phase of espresso brewing. This process allows the water you added during fill to soak through more evenly, but do be aware that different soaks will affect the clarity balance of the final beverage. There is certainly extraction happening in this phase; it's easiest to understand it as immersion brewing like in a french press.

### Percolation
The percolation phase is where the magic happens. Water is flowing through the coffee and extracting soluble material. Some general guides exist for understanding a reasonable flow rate during this phase. Most of the time based dialing info you've heard in the past comes from managing the contact time in percolation. Typical flow rates for a standard espresso paradigm probably look something like the following:

* Ristretto ratios (1:1.5 or less)

   <1ml/s in the cup
* Normale (1:1.5-1:2.5)

   ~1ml/s in the cup
* Lungo (1:2.5-1:3.5)

   2ml/s in the cup
* Allongé (1:3.5 and up)

   \>2ml/s in the cup

### Taper
Towards the end of many shots, you've lost 20% or more of the original mass of the coffee puck. If your puck integrity is degrading unreasonably, your flow rate is faster than you wanted, and/or channels are forming you can start to reduce flow and/or pressure and allow those problems to be corrected. Channeling is starting to seem like it is perhaps a little harder to define and identify than previously thought, so be aware that simply looking at the bottomless is not likely to tell you how severe your channeling issues are. Look for flavors that may be linked to channeling like excess bitterness or astringency rather than spritzers or 'bald spots' (which are simply caused by lower viscosity fluid towards the end of extraction.) Please note that just because a shot visually appears to need a taper doesn't mean that it does. Even extractions can still accelerate wildly at the end.

## Picking suitable profiles
One of the hardest things about making high and even extractions with an adjustable profiler is getting the coffee wetted relatively evenly. The first two stages of the profile you pick have a large impact on how extreme the gradient between the top and bottom of the puck is. I'm an advocate for rapid fill and short hold schemas; they get the coffee wet from top to bottom quickly and allow the user to move on to the next phase with no ill effects. Because there is a relatively large gradient of wetness in the puck using very slow filling profiles, I tend to avoid recommending this method.

We've already covered the primary benefit you can derive from using a profiler. As a reminder, you can adjust the flow rate through your coffee more independtly of the grind size. In order to pick our profile, we're determining what level of extraction we want for our chosen strength and then modulating our design for clarity or texture balance. If I want a 10% TDS shot at 28% extraction with reasonably high clarity, there is probably only one profile capable of doing this.

Simply put, I recommend a few base profiles that are fairly adaptable. They're listed here from high to low extraction.

1. Blooming allongé 
   
   Recommended for ultra light coffees and exceptionally high flavor clarity, especially when brewing nordic style filter roasts. I use an ultra fine or turkish grind and don't recommend this profile if your grinder isn't very well aligned. My current method is to use my known debit and a timer to add a little less than twice the dry weight of the puck in water as quickly as is reasonable (7ish ml/s) before closing the valve. I leave the valve closed until pressure returns to 1 bar and generally see about 4-10g in the cup at this point. If you're using a pressure profiler, try starting by ramping to 4-5 bar and then slow ramp back to 1-2 bar. I ramp to a debit of about 4.5 ml/s quite quickly and hold. Pressure rarely exceeds 6 bar and should taper naturally.

   This profile is best used when you want fairly high flavor clarity but still require extremely high extraction. The texture will be relatively thin and filter like.
   
   #### Blooming Allongé with a needle valve profiler
      - Fill at ~7-8ml/s (if possible)
      - Soak by closing valve fully and bloom til 1 bar
      - Percolate at 4.5ml/s debit position 
         -  Flow into cup at >2ml/s
         -  Pressure should not exceed 6 bar, adjust grind as needed.  

2. Blooming espresso

   Recommended for light to medium light coffees when you're looking for a fair amount of blending, a lot of texture, and high extraction. There are two primary versions of this profile. My current method is to use my known debit and a timer to add roughly twice the dry weight of the puck in water as quickly as is reasonable (7ish ml/s) before closing the valve. The classic method is to leave the valve closed for 30 seconds, aiming for first drips around this time. Getting drips or even a small amount of flow sooner is ok if you can’t grind finer. Further use has suggested that you can set an adaptive bloom; basically close at the desired pressure spike (5-7 bar) and open back up around 2 bar.
   
   If you're using a pressure profiler, try starting by ramping to 5-9 bar and then smoothly ramp back to 2 bar. I relatively smoothly ramp to 9 bar and hold after, though a taper could be useful if you believe you are prone to channeling.

   Some coffees will just fall apart in the percolation phase using the classic blooming profile. If you're grinding as fine as you can and managing your puck prep well you may need to switch to a different profile. I'd first suggest the adaptive bloom variant, the blooming allongé if you need more extraction, the allongé or variant if you need about the same but want more clarity, or the modified dipper if you're working with something realtively developed.

   If the blooming profile is extracting too high for what you are thinking of as medium light, it’s probably more developed than you realize. You can cut the ratio shorter if the concentration won’t be a problem or cut shorter and add some water if it is. Otherwise, see the modified dipper suggested profile.
   This profile is useful up to 1:3, but expect extremely high flavor intensity relative to the ratio.
   
   #### Classic Bloom with a needle valve profiler
      - Fill at ~7-8ml/s until the pressure reach 6-7 bar (if possible)
      - Soak by closing the valve fully and leave for 30s
      - Open valve to a flow rate that allows you to build to desired pressure
      - Taper if desired

    #### Adaptive Bloom with a needle valve profiler
      - Fill at ~7-8ml/s until pressure reaches 6-7 bar (if possible)
      - Soak by closing the valve fully and allow pressure to return to ~2 bar (adjust to taste)
      - Open valve to a flow rate that allows you to build to desired pressure
      - Taper if desired
 
3. Allongé, turbo, and yeet

    An allongé simple profile; grind a little coarser than normal and set debit to 4.5ml/s. For a pressure profiler, try 4-6 bar. Let it rip to a 1:4-1:5 ratio. Best for really light coffees, especially those that don't seem to be cooperating with the blooming version of this shot. This does extract a bit lower but is a higher clarity profile. This does mean it gives up a bit of thickness. I try to aim for a ballpark time of 30s.

    The turbo is bascially an allongé but shorter. It can be pulled as short as you like, but 1:3 is the original design. Set debit as you would for a bloom and cut back as your gauge reads 6bar. You can also set an adjustable pump bypass or over-pressure valve (OPV) to 6bar and just leave your paddle in place. Let it rip to your desired ratio, maintaining pressure as best you can and aiming for a very short time of 20s or less. You can grind finer and add an adaptive bloom to the start as well. This is a good clarity profile, but lower in texture. Works for coffees of all types, and you can find more about the turbo (and dialing it by ratio) at https://strivefortone.com/2020/09/19/low-pressure-turbo-shots-and-the-perfect-espresso/
    
    A derivative profile of the turbo has popped up recently affectionatly called a yeet. You set the debit full open and let the pump rip. The grind should be coarse enough that you spike quickly up to 6-9 bar (to fit your preference) and have pressure sag as the pump just can't keep up. Times should be very short. This is probably the highest clarity profile I've found so far. Silky texture.

   #### Allongé with a needle valve profiler
      - Set valve debit position to ~4.5ml/s
      - Check pressure and adjust grind to make sure it's hitting near 6 bar.

   #### Turbo with a needle valve profiler
      - Set valve debit position to ~7-8ml/s (if possible)
      - Catch the ramp up at ~6 bar and pull the needle closed to maintain this

   #### Yeet with a needle valve profiler
      - Set valve debit position to ~7-8ml/s (if possible)
      - Yeet
      
4. Modified Dipper

    We’re going to quickly add water at the same rate we did with the bloom and manipulate the paddle to keep around 2-3 bar of pressure reading on the gauge. Hold here until first drips and then ramp to 7-8 bar. Puck erosion or paddle manipulation can be used for tapering if channels tend to form, but I hold the pressure up if the specific bean can handle it. Use ratio to dial extraction and strength, keeping in mind that you can always add water if your shot is too strong. Darker roasts can be overdosed relative to the basket if you’re a texture lover, but I don’t suggest you do this for mediums. Texture seems to improve with longer holds with a relatively fine grind, though shorter holds will give more clarity if desired.

   #### Dipper with a needle valve profiler
      - Set valve debit position to ~7-8ml/s (if possible)
      - Catch the ramp up at ~1-4 bar (your preference) and modulate the needle to hold
      - Hold at that pressure for 5-20 seconds
      - Return to a percolation position that achieves your desired pressure

## The Slayer Profile
I used this for a long time and include it here because you have likely heard about it, associate slayer with high quality espresso, and will try it anyway. I don't recommend this recipe because it is not as efficient at soaking the puck evenly, but I do like it for ease of use. Expect a slightly less even tasting extraction that is still reasonably high.

The slayer profile is defined by three flow points; off, pre, and percolation. Off is 0ml/s, pre is traditonally 1-2ml/s, and percolation is the full flow of the pump. For practical purposes, I suggest finding a 1.5ml/s point of reference on your controller and working from there.

Use the slayer profile by setting the flow controller to the preinfusion setpoint and waiting for the gauge to ramp to full pressure. At this point, you can fully open the flow valve to 7+ml/s or set it to any other flow point. I generally put mine a bit lower to let pressure naturally taper so I can get a nice taper late in the shot. Allow the shot to finish as it will.

The alternative slayer profile is pre, percolation, pre. Basically you would run the machine at the pre mark until brew pressure is reached, open to percolation flow, and then close the needle back to pre flow to taper off and finish. Why you would ever do this with an on the fly flow controller is beyond me, but feel free to try.

## Dialing blooming profiles
This sounds super tricky, but for the most part you’re going to set a ‘reasonable grind’ that is quite small. This grind size can really be any starting point, but I recommend starting with a quick adaptive bloom reaching 7 bar and returning to 2 in 15 seconds or less from pump on. When it is time to open the valve back up, don’t open it crazy slow; a slow ramp makes it hard to build up to a reasonable pressure in the percolation phase.

When you want to modulate taste you can do it a few ways.

   1. Acid Balance - This is primarily done through modulating extraction. I generally start with ratio, then temp, then I'll adjust grind size and flow rate. If I already know what I'll need the order doesn't matter, but that's an easy way to work through it. Check the preferential extraction guide for more details.
   2. Clarity - Shorter contact times generally increase clarity, longer creates a more blended profile. You can modulate this through bloom timing, percolation pressure/flow, or grind size.
   3. Texture - If you're looking for thicker texture I think the easiest way is to dose a thicker, coarser grind. This seems to allow a turbulent flow that creates some emulsification as the percolation goes on. Adjusting the bloom to work for this is easy enough; you probably need a lower initial peak pressure and may or may not need to open the valve at a higher pressure (like 3-4 bar) so the puck doesn't soften too much.

## Purposefully clogging your basket
This is where it gets a little silly. You're going to grind fine enough that there is no saving the puck. There are then two ways to take it when the puck itself can sit at 9-10 bars of pressure for the entire time.

### The Clogger Profile
This profile can even be done on a machine without flow control. Be just like Elsa and let it go. Walk away. Come back later. Let it hit a ratio you would normally use for your roast profile, and just be patient. 3-5 minutes shots might not be as bad as you think. When it has hit your desired ratio, take a sip, and see if you want to sink it or not. While you wait, you can always adjust the grind size for the next shot and prep it with how long this one will take.

Well, you lost nothing since the beans were already ground. How did it taste? Better than you expected?  It was either a good shot and enforced the mantra of "taste every brew," or it was bad, and you shouldn't use it for this coffee. Try it again the next time it happens. Maybe you'll find a coffee you prefer at this odd end of forced emulsion.

Originally called "Low and Slow" by one of its advocates on Discord, SpRobert decided "Clogger" makes more sense since that is exactly what the espresso machine is doing.

### The Wave Profile
Take a page out of surfing and just be calm and ride that pressure reading up and down.

A recent profile developed by the same person who coined the profile above, SpRobert on Discord describes this profile as "gnarly tasty" and suggests you give it a try as he continues to desk surf inside while listening to the Beach Boys. The puck should never want to decline in peak pressure, but if it does, just keep following the profile. It's meant to blend the coffee without muting the acidity entirely, and the next time you try it you can just grind finer to where it will keep staying at that higher pressure if you want to. It's also just pretty fun. Sometimes you miss your ratio because you had so much fun, and it still tastes fine.

   1. Ride the wave up. Fill fast, let it peak at 9-10 bars, and then cut flow.
   2. Ride the wave down. Let the pressure gauge fall to <1 bar and open flow at full blast again.
   3. Repeat steps 1 and 2 until you're at your desired ratio.

If you graph this it should look like a Sin wave.

This profile was meant to integrate more than blend, and surprisingly the multiple blooms don't entirely kill the acidity. The changes in pressure do not degrade the puck as much as you might have thought since you're not evacuating the water suddenly through a valve so the puck still comes out plenty stable and compact, just like any blooming profile, but you keep hammering it and backing off to let the water find a natural balance on its own on the way out.

## Making filter style coffee (AKA The Sprover)
If you're considering making filter coffee in your profiling espresso machine the sprover is your best bet. Basically, pick a grind size coarser than the allonge and dose a little under your basket's rated size. I like 15g in a 20g basket to keep the shower screen clean. WDT and tamp as usual, lock in, and pull a shot with an input flow rate between 1.5 and 4.5ml/s. 

When you pick your flow rate, make sure that you're not building a bunch of pressure. You can fill the headspace at any speed between 1 and 7ml/s (I prefer fast filling) but don't let the gauge climb above 1.5 bar. Once the needle starts to move adjust flow to your intended rate. It's ok to use a slower flow rate to get things moving if you need to. You might get a little emulsification of the oils which can just be stirred in.

Dial the ratio to match your grind size. I have some timings and sizes that work well for me, but my general guide is aim for something between 1:10 and 1:14. The finer your grind the tighter the ratio should be. If you want to reduce strength after extraction adding clean water will take care of that. Dial extraction by adjusting ratio and grind size.

A reasonable starting point might look like this: 15g:195g, 2ml/s debit, flow for around 100s. You can dial stronger from here by grinding finer and cutting the output side of the ratio to as low as 150g or weaker by adding water and/or dialing coarser and extending the output ratio to 210g. Infusion speed can be changed with debit adjustments; I like faster flow so long as pressure isn't climbing since this nets me more clarity and a silkier texture.

If you want to cut some oils and fines out of the final brew, add a paper and or micromesh filter under the puck before prepping. I find the bed filtration to be very good with my setup so I skip this. YMMV.

## A final note about embracing turbos
This guide is reasonably exhaustive because the journey is important, but I'd strongly encourage you to consider rewriting the part of your brain that tells you fast extractions at low pressure won't work. I've recently been pulling many turbo shots and think that they're the best bet for getting to tasty quickly. There are a variety of benefits, not the least of which is modulating the amount of chlorogenic acid extracted, altering bitter balance, reducing unevenness of both flow and extraction, practically eliminating astringency, and an embrace of dial by ratio mechanics. Shots as short as 11 seconds including nearly 4 seconds of fill have been delicious and fully textured, so consider this your call to action!
## Getting Help and Moving Forward
Join the discord through the link on the home page and ask in #advanced-espresso. We can help you calibrate unusual machines, reform flow profiles into pressure driven profiles, or just talk you through finding a good starting point on your grinder. If you want to ask a specific question about the guide and not about profiling, feel free to @ me directly. My discord username is @shotwell#7641

I strongly encourage everyone to adopt a beginner's mindset. We don't know what will happen unless we try, so please don't feel like you need permission to do something with espresso. If you made a change and something tasted better, try to go even further in the new direction. Try something in the middle. Break the rules, and have fun.
