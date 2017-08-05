---
published: false
---
_Some extended notes and description of Nest battery  and HVAC issues…_

### My story

Very quickly - Nest thermostat installed two years ago. Last night, no A/C on at all, Nest appears dead, little green blinking light. Call Nest, check voltages, suspect odd bevior from blower electricals, recharge the Nest via USB. Repeat. Call local A/C team to check on blower/system, they say the Nest NiCad battery is dead, need to run a Common wire, which will cost $427. Whoa, what?!?

### Background

First, residential HVAC wiring, especially, older wiring, is very basic. That helps to keep things simple and working, but also means that it is not a great match for slapping on an “internet of things” smart thermostat.
 
Traditionally, older HVAC may have simple wiring designed to just turn on and off the A/C (or blower) or heat/furnace when the *mechanical* thermostat says to.  All well and good.
 
The Nest, however, is a (very) small computer that likes to actually run its electronics all the time (and connect to the internet and do various things). That means it needs electricity all the time but unlike a real desktop PC, it has no large wall plug and cable. Instead it has a (very) small (and flat) lithium-ion battery (No local A/C team, not a NiCad!). Normally, the Nest computer actually runs off power from its lithium-ion battery , not from any house power source. The bad news is that the Nest computer needs more electricity than a small battery can hold for very long. So keeping the battery charged up is key.
 
If the battery somehow gets to a low charge state, then it will shut most of the Nest computer itself off (and with it, shut off the A/C or heat), so that it can conserve the last remaining dregs of battery. A little green dot will blink at the top of the Nest; meanwhile the screen will be blank. At this point, you and I will panic and try to find out why the HVAC is off. One short-term fix is to take the Nest off the wall and re-charge the battery via the Micro-USB charge port on the back. This is the fail-stop re-charge solution and works, though it takes maybe 45 minutes to 2 hours for the battery to get fully charged.
 
But why would the battery get in to that low charge state?

### How does the battery get charged?

Turns out there are two ways the Nest get extra electricity to keep the battery charged. If the HVAC wiring in the home is somewhat recent (within 10 years, 15 years?) or was built by an electrical nerd, then it may have an extra wire available which can provide a little bit of power all the time. This wire is confusingly called the “Common” wire. If you have a Common wire, then when you install a Nest, you’ll attach that to the “C” wire port, and that will be used to charge the Nest battery continuously.
 
(Digression: Of course, if there’s a constant source of power from the Common wire, why have a battery? In case of power outages. Oh, OK. Except the battery only lasts several hours anyway, so long-term outages mean you’ll have an HVAC outage to deal with no matter what. Sorry.)
 
The other way that the Nest handles charging the battery is by “stealing” a bit of electricity from the A/C or heating wires *when they are running*.  Usually, during the summer or winter, there’s enough time that some system is running that there’s plenty of time to get the battery charged during day or night. Sometimes, however, the HVAC systems will not have run in a while, the battery charge will drop, and the Nest will respond by turning on the A/C, blower, or heater for a while, for the sole purpose of re-charging the battery. (Digression: Yes, this is an odd thing indeed from a device that advertises that it can save you energy with fancy awareness and learning algorithms.)
 
Now, there may be some random set of temperature circumstances such that the Nest battery just doesn’t get charged enough by “stealing” electricity. As mentioned above, in this case you may need to Micro-USB charge the Nest to get it to reboot and re-activate your HVAC.
 
Anyway, as long as the lithium-ion battery is getting charged, say through the Common wire or enough cycling of HVAC, you’re all set.
 
But if there’s a systemic problem – if the A/C or heating unit isn’t cycling properly or turning off prematurely, or the Common wire has snapped, or the HVAC circuit breakers have tripped – then the Nest battery will get drained. In this case, you’ll probably be trying a few things with no success until you realize that it is the A/C or heater or whatever that is actually broken and needs fixing before you can even worry about the Nest. (Digression: And note how complicated it is to try and fix your HVAC components when there’s no reliable control switch to turn things on/off !  The Nest should have a little manual on/off switch on the mail wall bracket for just such an occasion.) Once you’ve fixed whatever system was broken, then the Nest will be able to re-charge itself, or you’ll want to do a Micro-USB re-charge.
 
Come to think of it, it would have been great if the Nest did have a real wall plug and cable!
 
BTW, it’s a special lithium-ion battery – see the [iFix battery replacement](https://www.ifixit.com/Guide/Nest+Learning+Thermostat+2nd+Generation+Battery+Replacement/30626)
 
BTW, if you install your Nest thermostat yourself, there's a [2-year warranty](https://nest.com/legal/warranty/thermostat/) on it.
