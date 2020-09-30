# Drones

## A video on adding a gimbal and camera to a home made drone

It's exceptionally detailed.

https://www.youtube.com/watch?v=ryGdH7dILXo

## Video on different drones at different grades

- start with tiny hawk
- move on to modular ready-to-fly

https://www.youtube.com/watch?v=DLJHdM4-LuI

## How to Build a Cinematic FPV Racing Drone - DJI FPV

Contains a link to four other FPV drone experts that you should watch
videos from.

https://www.youtube.com/watch?v=X79qX_kAloY


# FPV Shopping list

Great link to Tiny Hawk.

https://www.fpvknowitall.com/fpv-shopping-list-rtf/

Video on the TinyHawk

https://www.youtube.com/watch?time_continue=806&v=4TDNEE_HUy4

# How to hook up RT to sim

Might not be the best link
https://oscarliang.com/betaflight-fc-fpv-simulator/

# Soldering Station with magnifying glass

https://www.amazon.com/dp/B007CDJMOS?tag=duckduckgo-ffab-20&linkCode=osi&th=1&psc=1


##

https://www.modelflight.com.au/blog/difference-between-rtf-bnf-pnp-arf

- RTF stands for Ready-to-Fly and it means the model you are buying comes
  complete with everything you need to get started - straight from the box! Have
  look at our ready to fly drones.

- RTR stands for Ready-to-Run and it means that the RC car or boat comes with
  the transmitter, battery and charger. You can start racing without requiring
  any extra component.

- BNF stands for Bind-N-Fly.  Bind-N-Fly products come with everything you need
  except for a transmitter.  With BNF products you can use the transmitter of
  your choice and bind it to the receiver included with the model.

- PNP stands for Plug-N-Play. Plug-N-Play products come with everything you need
  except for a transmitter, receiver battery and charger.  It does contain
  servos, motor and ESC.

- ARF stands for Almost-Ready-to-Fly, this means the model needs some additional
  "need to complete" items before you can start flying.  Common additional items
  include servo's, motor, electronics, batteries and even glue.


# UAV Coach

A great resource for learning the basics about how to control these things.

https://uavcoach.com/how-to-fly-a-quadcopter-guide/


## Drone Clubs in Australia

http://aufpv.org.au/clubs/


# DVR in Goggles is important

- Otherwise how do you review your footage when you lose it?

# Radio Transmitters

Either
- AUD$300. Taranis qx7 with upgraded M7 Hall Effect Gimbals [Link](https://www.banggood.com/FrSky-Taranis-Q-X7S-ACCESS-2_4GHz-24CH-Mode2-Transmitter-M7-Hall-sensor-Gimbals-and-PARA-Wireless-Trainer-Function-with-R9M-2019-Long-Range-Module-for-RC-Drone-p-1612733.html?rmmds=search&ID=5197096279155&cur_warehouse=CN)
- AUD$400. Taranis x9d Plus SE [Link](https://www.banggood.com/FrSky-Taranis-X9D-Plus-SE-2019-24CH-ACCESS-ACCST-D16-Mode2-Transmitter-M9-Hall-Sensor-Gimbal-PARA-Wireless-Training-Function-for-RC-Drone-p-1537807.html?rmmds=search&ID=62655746279155&cur_warehouse=CN)

# TinyHawk Instruction Manual

https://emax-usa.com/documents/Tinyhawk_RTF_Instruction_Manual_v1.3.pdf

# RC Rates

RC Rate, Expo, Super Rate, etc.

https://oscarliang.com/rc-roll-pitch-yaw-rate-cleanflight

# Tinyhawk debugging

On Mon 15 June 2020 I had some problems with the transmitter not connecting to
the Tinyhawk. I needed to follow the instrucitons here:

https://emaxusa2.freshdesk.com/support/solutions/articles/19000108267-tinyhawk-manuals-cli-firmware-for-rtf-bnf-v1-v2

It involved

1. Downloading the firmware and flashing the TinyHawk with BetaFlight

> TinyHawk BNF/RTF v2 custom firmware (load from local after downloading, and use Configurator 10.5.1 https://github.com/betaflight/betaflight-configurator/releases/tag/10.5.1)
https://drive.google.com/file/d/1xbCc62xm-7xuotDmWV-4LbkzBlr5fH4f/view



2. Copying and pasting the CLI commands into the CLI window and running them.

> TinyHawk RTF v2 CLI
https://drive.google.com/file/d/1p-UK-UvZQyPYOw9xOLoKVlO2eMI-YUBD/view?usp=sharing

File is also [here](../../misc/TinyHawk-RTF-MatekF411RX-4.0.0.txt)

Binding

> For v2, plug a charged lipo battery to the drone. The next step is easier if
> the battery is hanging free, out of the battery mount. Using a non-metallic
> object (or even just pushing/flexing the battery mount), hold the Bind button
> on the bottom of the main board for several seconds.


> For E6 transmitter on both v1 and v2, turn on your E6 transmitter and then
> hold the throttle and pitch trim buttons down until there is a slight red LED
> color showing through the power indicator ring. Keep the E6 transmitter at
> least 5 feet away from the drone to allow for proper binding. Unplug the lipo
> battery from the drone. Turn off the E6 transmitter.

-----

## The steps

1. Plug a charged lipo battery to the drone. Hold the Bind button on the bottom
of the main board for several seconds.

2. Turn on your E6 transmitter and then hold the throttle and pitch trim buttons down until there is a slight red LED color showing through the power indicator ring. Keep the E6 transmitter at least 5 feet away from the drone to allow for proper binding.

 3. Unplug the lipo battery from the drone.

4. Turn off the E6 transmitter.

-----

Okay, looks like there might be some updated firmware:

https://emaxusa2.freshdesk.com/support/solutions/articles/19000108757-tinyhawk-ii-rtf-bnf-manual-firmware-cli-binding


----


## My flight controller Matek f411 RX

Apparently this is my flight controller...

Wiring diagram shown here

http://www.mateksys.com/?portfolio=f411-one#tab-id-3


But I'm not sure this is true for the TinyHawk II.  

## TinyHawk 2 known to fail

https://www.reddit.com/r/Quadcopter/comments/eyvzl1/tinyhawk_ii_binding_issue/

## Software Defined Radios

Matt Chapman tells me that SDRs are what I would use for checking the signals
received by 2.4Ghz and 5.8Ghz transmitters/receivers.

Here's a list of boards. Somewhat expensive.

https://en.wikipedia.org/wiki/List_of_software-defined_radios

## 3-inch Cinematic FPV drone

Flies slower and easier to control. Probably what you want.

https://www.youtube.com/watch?v=4bDZA2gT3OE

## DJI Digital FPV

Some harsh truths on the DJI Digital FPV system.

https://www.youtube.com/watch?v=DQaTm1O81H4

Aussie reaction to DJI Digital FPV system

https://www.youtube.com/watch?v=XIByZACpvCo

Can you use another transmitter for the DJI Digital FPV system?

https://forum.dji.com/thread-208066-1-1.html

How to use your own transmitter. Turns out that BetaFlight will support the
DJI low latency protocol.

https://www.youtube.com/watch?v=mA9eAroS_6I

## Extra things you need to buy

https://www.youtube.com/watch?v=O-8nAE8FsjU

## What does KV mean?

It doesn't mean kilovolts. It means RPM per volt.

## ESC = electric speed controller

 ESC converts to AC from DC too!

## GPS mode in Betaflight is hard to configure and get right

https://www.youtube.com/watch?v=GE6K9HiTO90

He runs through the settings at the end:

## GoPro

- Put filters on them
- Set shutter speed correctly

## Tutorial on how to edit Freestyle videos with Adobe Premier

https://www.youtube.com/watch?v=60mvHEX81kg


## Receivers

Futaba R3206SBM used by Nurk
https://www.youtube.com/watch?v=jL91jcG9FJw&t=11m34s

## A guide to 1s/2s/3s balance ports and LiPo batteries

http://www.tjinguytech.com/charging-how-tos/balance-connectors


## Latency is a factor in cameras

## PCB Plate remove from Run Cam Nano 2

On 4 July I somehow managed to remove the PCB plate on my Run Cam Nano 2 board.

It almost certainly happened because my soldering iron was too hot:
https://www.instructables.com/id/How-to-Repair-Damaged-Printed-Circuit-Board-Pads/


## Shrink tubes and Flux Paste

Tonight I just learned about two things: shrink tubes and flux paste.

Shrink tubes are insulation that goes around wire joins. You can use a soldering iron to shrink the tube around the join.

Flux paste is used when soldering two wires together.
https://www.youtube.com/watch?v=bGckVJeG6b8

Soldering wires with flux paste.

## Wire Gauges and Drones

How big should your wires be?

https://oscarliang.com/wire-awg-chart-quadcopter-rc/

## All about propellors

I still don't understand pitch.

https://www.getfpv.com/learn/new-to-fpv/all-about-multirotor-fpv-drone-propellers/

## Insta360 Go - different  between FPV stabilization and Flow Stabilization modes

https://360rumors.com/insta360-go-3pv-fpv-stabilization-mode/

## Mavic Air 2 review

This review has names for the segments of the video. I need to find out how this is done in YouTube Studio.

https://www.youtube.com/watch?v=Z-pRNsheLXM


## EVA Foam seems to be the way to go

Great for cosplay too. Many YouTube films on it.

## Best FPV video I have seen

I want to be this good one day: https://www.youtube.com/watch?v=K10V_8t6Lbg

Flying, editing and sound design are top notch.

## A need a lipo bunker!

After seeing several videos of LiPo battery fires I realise I desperately need a LiPo bunker. I simply cannot be charging them inside my office!

- fire extinguisher
- smoke alarm

Some LiPo batteries have over-charge and over-discharge protection circuits in
them. I think I will have to buy these from now on:

 https://www.youtube.com/watch?v=osfgkFyq7lA

This looked like a cheap but good solution:

https://www.youtube.com/watch?v=ZKbp8zfQ5qA


## A long video explaining everything about LiPo Batteries:

Watched: Not yet
https://www.youtube.com/watch?v=eKLHD7_zzCE


## Warning signs your LiPo is becoming dangerous

https://www.youtube.com/watch?v=l43Kx0OxpKI

- internal resistance is something you might want to check for
https://www.youtube.com/watch?v=l43Kx0OxpKI&t=7m10s

- parallel charging a multi-cell pack with a bad cell kills the
  same cell in the other packs!
  https://www.youtube.com/watch?v=l43Kx0OxpKI&t=13m0s

# Consider LiFe or Lion batteries

LiPo vs LiFe(PO4)

https://www.youtube.com/watch?v=KXLvljqde0M
https://www.youtube.com/watch?v=XymqQ-YlfJ0

LiPo vs Li-ion

https://www.youtube.com/watch?v=ltUIU79O3Gc

# Calibrating your Betaflight current Sensor

Sometimes it can give values that are too high and so you have to
stop flying before you should have.

https://www.youtube.com/watch?v=pj_CaMZ98g4

# Training tips

https://www.youtube.com/watch?v=aX9T2GSGrJ0

# Long Range drones

TBS CrossFire or Frsky R9 are the two options.
Also some good info about GPS and iNav (whatever that is)

https://www.youtube.com/watch?v=YW1LSB_uhP4

# Reduce Jelly (Jello) using a mounting plate with piano wire

https://oscarliang.com/anti-vibration-piano-wire-camera-mount/

- This video shows the effect using iSeismometer https://www.youtube.com/watch?v=4ac2mV3ht0g
- With wire rope:
   * https://www.youtube.com/watch?v=cajoxGhFQck
   * https://www.youtube.com/watch?v=nEaTO2twSxc

This comment was interesting:

> I have used these exact isolators at work to isolate million (or more) dollar
> telescopes during road transport by large truck. The fact that my company
> chose this solution for expensive high-risk equipment says a lot. Many other
> companies use the same system for all kinds of isolators in different
> applications. They pack the wires with oil in commercial applications to
> greatly increase the damping. They are superior to rubber isolators for
> reasons I'll describe below in as few words as possible.
>
> The friction between the steel wires provides superior isolation compared to
> rubber spacers, which have no surface-to-surface contact going on during
> flight.  Rubber spacers still work since high frequency vibrations are not
> transmitted through soft low frequency rubber spacers. Shock absorbers on cars
> are tuned to around 3 Hz (fairly low) for this same reason.
>
> If anyone has dropped one of those rubber balls that bounce nearly forever,
> then you'll understand that most rubber has very little vibration damping
> ability when used as an isolator. The only solution to that is to drill a
> couple small and symmetric radial hole patterns (rough tip drill bit needed)
> in the rubber isolators to drop their stiffness until they are just stiff
> enough for your setup so your camera doesn't bounce & twist all over, while
> being as soft as possible for isolation reasons. They still won't work as well
> as the rope isolator here, for those of us that need the best picture out of
> our cameras.

Looks like you could make on that mounts on top: https://www.youtube.com/watch?v=dwzzKnhk0K8

And then there's this el cheapo solution: https://www.youtube.com/watch?v=PuNhiJAVum0

Here are the build instructions for creating a wire rope isolator.
https://www.youtube.com/watch?v=Ke1R2alEhnI

Cutting wire rope with a blow-torch.
https://www.youtube.com/watch?v=LnTHZhTkg2U

Here's a way to do it with electrical tape at a "cold chisel"

https://www.youtube.com/watch?v=WzUhIlnvwZg

## Which batteries are the best?

- https://www.youtube.com/watch?v=uLb9WD2UhJc

Comparisons can be found here:

- https://docs.google.com/spreadsheets/d/10-0JsOiuIFB6GCJF4rX_foSdA9Cx5UnjYR3UlZa7gA4/edit?usp=sharing

## Does mAh add when connecting batteries in series?

https://electronics.stackexchange.com/questions/20701/adding-mah-when-wiring-battery-cells-in-series

## Faulty EMAX E6 throttle was causing problems with flying drone

I discovered today that I couldn't hover my drone. Why? My remote's
throttle isn't working.

This video here shows exactly the problem I've having!  https://www.youtube.com/watch?v=N1wlCfmossE

Here is some discussion on how to fix it:

https://www.reddit.com/r/Multicopter/comments/fqmz1r/emax_e6_transmitter_how_to_fix_throttle_gimbal/


## Smoke stopper should be used when building your own drone

https://www.amazon.com/dp/B088TVVNVM/ref=as_li_ss_tl?ie=UTF8&linkCode=sl1&tag=fpvknowitall-web-20&linkId=4342752bc762a85a5188a0ffbd8b73a2&language=en_US

## Calibrating the EMAX E6 Transmitter remote

![](assets/drones-d61768de.png)


## Fast FPV order in Australia

https://www.fpvfaster.com.au

## Lighter air unit compatible with DJI Digital FPV system

Caddx Vista Digital HD system. Weights 29g vs about 46g for full air unit.

## Broken brushless motors

Looks like I broke the little copper wires attached to the wires of two of the brushless motors. The first happened after a crash. The second happened when I
unscrewed another brushless motor from its mount and the ran current through it. It bobbled around and then snapped one of its wires...

https://www.rcuniverse.com/forum/brushed-brushless-motors-speed-controls-gear-drives-123/7818944-broken-wires-motor-repair.html


## Race Wire (it's not really wire)

- reduces weight
- standardise your motor wire length and use Race Wire.

See:
* https://www.getfpv.com/learn/fpv-essentials/fpv-drone-wire/
* https://www.youtube.com/watch?v=iBJ3k6aPJ8U
* Joshua Bardwell https://www.youtube.com/watch?v=eKzZPyxuGe4

## Australian stores

- https://www.fpvquads.com.au/
- https://buzzfpv.com.au
- https://fpvfaster.com.au
- https://www.dronepartsgarage.com.au/
- https://www.metrohobbies.com.au
- https://www.multirotorshop.com.au
- https://www.nextfpv.com.au/
- https://www.hobbyman.com.au/
- https://www.risingsunfpv.com.au/

## Lumenier is a US based drone manufacturer

https://www.lumenier.com/

## Locations

- Team Black Sheep: Hong Kong

## More on motors

- 3D printing motors: https://www.youtube.com/watch?v=Ha0ikqnP4vs
- removing enamel on copper wire using emery board: https://www.youtube.com/watch?v=Whc-Ddaz-Ss
- removing enamel on copper wire using rosin core solder: https://www.youtube.com/watch?v=0XQj8H5HR3M

- Rewinding tutorial: https://www.instructables.com/id/Rewinding-a-Brushless-Motor/
- Winding schemes:
   * http://www.bavaria-direct.co.za/scheme/common/#prettyPhoto
   * http://www.bavaria-direct.co.za/info/

Weak wires in motors:

https://fishpepper.de/2017/09/08/tutorial-replacing-stiff-motor-wires-with-flexible-ones-no-more-breaking-wires-br1103b/

Very detailed instructions on motors. Mathematics involved: https://www.instructables.com/id/Make-Your-Own-Miniature-Electric-Hub-Motor/

https://dronenodes.com/drone-motors-brushless-guide/

## On motor construction and the poor construction in China

https://www.youtube.com/watch?v=WtQYDsH3Cgk

## How a motor is made in China

https://www.youtube.com/watch?v=JlzruRmmnWI

## How to build a drone with Joshua Bardwell

https://www.youtube.com/watch?v=FEittnx42Zc

## How to build a drone for USD$99

https://www.youtube.com/watch?v=Avp8MurmeEY

## A 4" drone that has 18min flight time on 1000mAh 4S battery

https://www.youtube.com/watch?v=khL2Rxu2OD0
https://flywoo.net/collections/explorer-lr

And if you use a Li Ion pack you get 37min flight time!
https://www.youtube.com/watch?v=mZ7sogO778Q

## Botgrinder has amazing FPV moves

https://www.youtube.com/watch?v=BUFcJ2zhDlk

## Good guide on how to solder by Oscar Liang

https://oscarliang.com/soldering-guide/

## Deadcat is a framestyle that means props aren't in camera view

https://www.getfpv.com/lumenier-qav-r-2-slam-deadcat-freestyle-quadcopter-frame-5-6-7.html

## Snapmaker 2.0 - 3d printer, CNC, laser cutter

https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers

## Microscope

https://www.banggood.com/Andonstar-ADSM201-1080P-Full-HD-USB-Microscope-Magnifier-Long-Object-Distance-Microscope--p-1111802.html?akmClientCountry=AU&p=CS101558118042016088&utm_campaign=mesh&utm_content=tanghao&cur_warehouse=CN


## PCBWay

Get your own PCBs uploaded and printed!

https://www.pcbway.com/

## Service in Australia that does CNC for carbon fiber frames

http://carbonfiber.com.au/prod35.htm

Here's now to design your own using CAD software in Fusion360

https://www.youtube.com/watch?v=1FjzM1NhfzA

## Buzzers with built-in battery

https://oscarliang.com/drone-buzzers-with-battery/

## High discharge lithium ion may be the future of drone batteries

https://outcastdroneworks.com/products/2s7-4v-3250mah-lithium-ion-high-amperage-pack

## Tips on uploading to YouTube

https://oscarliang.com/upload-dji-fpv-footage-youtube/


## DJI FPV needs IMU data to stabilise correctly

https://www.rcgroups.com/forums/showpost.php?p=44515991&postcount=6248

## The MeCo Li Ion batteries I bought from BangGood are not 4000mAh

I almost certainly bought these batteries.
https://www.youtube.com/watch?v=kDAxgpAPOAY

## Debugging vibration in your quad

https://www.youtube.com/watch?v=Pz_X7d9zxMA

1:28 - motor vibration test


## How to check your motors for vibration

Go to the Motors tab

Set up to look at the accelerometer with refresh as 20ms and scale at 2.

![](assets/drones-ccf02e8e.png)

Spin up the motors and hopefully the values in the brackets should be below
0.03.


## Another video on PID tuning for vibration controls

https://www.youtube.com/watch?v=FnIh4rXX0jE

## Betaflight 4.2 PID Tuning notes

https://github.com/betaflight/betaflight/wiki/4.2-Tuning-Notes#quick-settings

A video showing the effect each of these PID tunes as is here: https://www.youtube.com/watch?v=eFTnlhQRCFo

## DJI FPV range: watch the Mbps to gauge your distance

https://oscarliang.com/signal-strength-dji-fpv/
