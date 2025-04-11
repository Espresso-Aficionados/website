---
layout: default
title: Vibration To Rotary Pump Modification For Home Espresso Machines
parent: Guides
nav_order: 14
---

# Vibration To Rotary Pump Modification For Home Espresso Machines
Many vibration pump machines have enough space inside for a small rotary vane or gear pump with an integrated motor. If you're after low noise and potentially more linear pump-based flow profiling, this conversion is often possible! However

## Things To Keep In Mind

### Does It Fit?
The first and probably most important question you'll need an answer to is whether or not you'll have space for the pump in question. Luckily, both ProCon and Fluid-O-Tech (FOT), who make these integrated pump-motor combos that are the best choice here, publish datasheets on their websites with measurements. They tend to be about 6-8" in length, which will fit in most prosumer vibration pump machines. However you will need to measure before you buy. With DC motors, you will also need some kind of AC-DC power supply at the right voltage.

### Here There Be Dragons
1.  This kind of modification requires understanding and being respectful of mains voltage electricity. It should not need to be said, but just in case it does: ***Mains Voltage Can Deliver A Lethal Shock.*** Modifications like this *must* be done with the machine off and unplugged from the wall, and all mains voltage carrying wires must have insulators around any terminals. You will need to test the machine with it open. Do not touch any internal parts when it is on unless you know for a fact that it is safe.
2. These pumps offer *hugely* higher flow rates than vibration pumps. You will absolutely need some kind of flow restriction, be that an adjustable needle valve, a fixed gicleur, or a way to reduce pump throughput on the fly. My machine's water debit jumped from roughly 6.7 ml/s to over 9 ml/s, and that's with a roughly 0.7mm orifice gicleur in the solenoid valve. 
3. You will need to figure out how to mount the pump in your machine. This can be... tricky. Follow the mounting instructions from the manufacturer.
4. Make sure the pump is NSF rated (this is important for food safety reasons) and can handle the pressure you're asking it to do. 
5. If you add a check valve (one way valve) after the pump (which you should, to avoid any backflow through the pump), you *must* have a relief valve for thermal expansion of the water as it heats. If not, your pressurized water lines can burst and spray water everywhere inside your machine. 
6. Rotary pumps really, *really* do not like running without water. It can damage them very quickly. Either plumb it in or make damn sure that your machine can't run itself out of water without shutting off.

## So What Do I Need?

### 1. The Pump:
#### Which Pump Type Should I Choose?
Both vane and gear pumps are what are known as *Rotary Pumps*, meaning that they use the rotation of a shaft to move fluid through them. However, this is where their similarities more or less end. 

##### Vane Pumps
Vane pumps are used on most commercial espresso machines and some high end home machines. They can have extremely high flow - even the miniaturized ones in question are at absolute minimum 15 gallon per hour pumps, more than twice that of an unrestricted vibration pump. You can easily replace two vibration pumps with a single vane pump - but more on that later.  They are quiet and low vibration, and are generally simpler to hook up. However, they lack the ability to easily do flow profiling by varying motor power, as their flow curves are less than linear with most of their range well into the top half of the motor's speed. These are a good choice if you're just after lower noise. AC motor powered rotary pumps are also available, which is a viable choice if you only want lower noise. 

##### Gear Pumps
Gear pumps are far less common on stock espresso machines, but they hold a few important advantages over standard vane pumps. They tend to be smaller, and their flow characteristics are roughly linear to rotational speed. The miniaturized ones tend to use brushless DC (BLDC) motors, which can easily have their speed (and therefore flow) varied. Generally, they're a better choice, but they can be harder to find and the advantages only really come in when you want to vary flow at the pump. They may also not have an integral bypass valve to limit output pressure. 

### 2. The wiring:
If your machine is like most home machines, the pump is directly powered from the control box via a relay or directly from the brew switch. However, this is mains voltage AC power and will not work on a 24V DC motor. For AC motors, the control box likely can't provide enough current without burning something. 
The easiest way to power a DC pump motor is by connecting a switching power supply's primary directly to mains and switching the secondary. Hook an SPST-NO (Single Pole, Single Throw, Normally Open) AC relay's coil up to where the vibration pump attaches either to the control box or to the brew switch. Connect the pump's wiring to the common terminal, and the output from one side of the power supply secondary to the NO terminal. This way, when the brain box sends the command to tell the pump to turn on, it behaves exactly the same way. 
For an AC motor, you can do largely the same thing, but skip the power supply - it's not needed. You will need a start capacitor however, though most come with them built in.

##### What Power Supply Should I Buy?
Generally speaking, you will want at least 150% of your pump's rated motor power. 60W motor? 90W power supply. 80W motor? 120W power supply. You get the idea. If you're going to mount it inside the machine, it must be able to withstand elevated temperatures of at least 70 degrees Celsius. Encapsulated power supplies from the likes of Mean Well and CUI are a good choice for compact internal mounting, but require essentially hacking into the machine's mains power. Externally mounted supplies like larger LED drivers or power bricks can plug directly into the wall, though they are less convenient and take up more space. 

##### Brushless DC Motor Control 
For RPM control on brushless motors, you will need [someone else fill this in, I'm not sure what is needed]



### 3. The Plumbing.
There isn't a huge amount that will need to change here versus stock; largely, you will only need the right fittings. Most machines use BSP (AKA Gas) threaded fittings, commonly 1/8 and 1/4. The hose from pump to boiler will either be stainless flex tubing with threaded ends You will need to find what works for your machine as it is not the same on all machines.
Both types will need a *check valve (AKA one-way valve, AKA non-return valve)* to prevent thermal expansion in the brew boiler from returning through the pump back to the tank. Vibration pumps have one built in as part of how they work, but rotaries do not. However, do keep in mind that you will absolutely, one hundred percent, no ifs ands or buts, need to keep a relief valve downstream of the pump. If you don't, thermal expansion of the brew water can cause  pressurized water lines, especially PTFE tubing, to burst. Luckily, you can reuse the OPV from the vibration pump for this - and it has no bearing on brew pressure, so you can just set it above the bypass valve on the rotary pump.
With all threaded fittings, PTFE thread tape will be your best friend to seal them against leaks. Make sure to wind it onto the threading the right way (that is, with the seam facing the opposite direction of the threads).


### 4. Replacing Two Pumps With One
Some home dual boilers like the Rancilio Silvia Pro and Breville Dual Boiler have two separate pumps for this as vibration pumps generally do not have enough throughput available to supply both simultaneously. If you have a higher flow pump, it can likely act as both the brew pump *and* the service boiler fill pump. To replace both, you will need to add a normally open 2-way solenoid valve (AC of your local mains current value) and another SPST-NO AC relay. The relays will need to be in parallel with one another so both will complete the pump power circuit irrespective of one another's current switch state.The 2-way solenoid is wired in series with the service fill pump relay so it will activate and allow water to enter the boiler. You will need to replace the boiler fitting and fill hose to make this work - a T fitting from the pump output instead of a single output fitting will be needed as well.

## Example Parts List


