---
title: "Schaublin 13: gearbox noise"
slug: sv13-gearnoise
date: 2024-01-14
coverImage: "gear-train-1.jpg"
tags:
- tech.turning
- tech.measuring
- schaublin-13

categories:
- machine overhauling
- schaublin 13

keywords:
- milling machine
- gear noise
- gear rattle
draft: true
---

By some reason I thought since the begining of the overhauling that
the gearbox was in a nice condition. Thus, I didn't reviewed it. In
fact, I didn't even emptied the oil. During the overhauling of the
SV13 the time arrived to check the gearbox. I switched the power
on... and the gearbox made an intense rattling noise in some speeds
:raised_eyebrow:.

<!--more-->

# Context #

This is a picture of the gear train when the «direct speed» is
selected: 

{{< figure src="gear-train-1.jpg" >}} 

In the picture, MS is the main shaft where the variable speed driver
belt is attached (to the right of this shaft). Over the main shaft
slides the assembly SG. The main shaft has a pinion G2 that is
permanently engaged to gear S3. At the same time, G2 is acts as a dog
clutch of the sliding gear SG: the right end of SG engages G2 and
makes the main shaft and the sliding gear to turn together. This is
the position shown in the picture. The gear SG is permanently engaged
to G1, the long gear that transmits the power to the milling machine
horizontal spindle.

You select the low speed by sliding SG to the left. Then SG engages to
the pinion of S3 shaft. Next picture shows the gear train in the low
speed position:

{{< figure src="gear-train-2.jpg" >}} 

Additionally, there is a intermediate position of SG where it is
engaged to no pinion and turns freely over main shaft. In this
position, the long gear G1 is unconnected to the main shaft.



After emptying the oil and disassembling the gearbox the following
facts were discovered:

1. The plain bronze bearing of the sliding gear SG was heavily worn:
   about 0.5 mm in the side of the gear and about 0.1 mm in the side
   of the dog clutch.
2. Bearings look nice enough. Maybe a bit of micro pitting. The big
   bearing supporting the main shaft pulley efforts may have a bit of
   play but nothing extremely important.
3. The gears do not have visible damage. Most of them looks like
   new. Indeed, the gear supporting the bearing play shows no signs of
   bad wearing.
4. It seems to me that the gearbox has not been never opened. However,
   the small cover plate has been opened for sure: I guess that the
   big bearing is not an original one.
5. The sliding gear assembly has a dog clutch that engages the pinion
   on the main shaft. This is really an internal gear that fits over
   the pinion. This part of the sliding appeared with some dents
   resulting from having been peened with a hammer. This really
   intrigued me as the gearbox seems never repaired. Do the guys at
   Schaublin use the hammer to adjust this part? Do they try to correct
   some out-of-round? Do they try to guarantee that the clutch slides
   in and out smoothly?
   
   {{< figure src="dog-clutch.jpg" >}}

# Plain bearing repair #

I asked Schaublin for a spare of the sliding gear. They answered that
they have no spares now although its not unusual to have some of
them. The spare part includes the main shaft and the sliding gear all
together. The price was high but I thought it is more or less
appropriate. The kindly give me the drawing of the bearing with its
tolerances.

{{< figure src="schaublin-drawing.jpg" >}}

I turned a new bearing according to the drawing. More in the tight
side of the tolerance. Replaced the worn bearing and assembled again
the gear train. Unfortunately, the clutch do not engaged smooth
enough. This was the result of a better fitting of the bearing!!  I
worked it until it fits smoothly but with no play.

The next video shows some details of the turning job and, the
following one, shows the smooth fitting of the clutch.

{{< youtube id="RvptHNiNIQM" >}}

{{< youtube id="pCuSIBRZTgs" >}}


# Gearbox with the new bearing rattles #

After assembling again he gearbox I tested it under power. When
assembling I reversed the long gear to take advantage of the best
looking part of it. To my annoyance, the gears train shows a
(rattling) sound under the direct speed, more audible when running at
low rpm.

# Why? #

I began a set of tests to gain some insight into the reasons why
the gearbox is making noise. I disassembled the gearbox again,
replaced the big bearing and assembled the box without the idle
shaft. I try to proceed by first understanding where the noise
originated.

From this, is clear that the noise comes from meshing of the sliding
gear and the long gear. However, the noise is only made when the
direct speed is used. Thus it seems that there is nothing to do with
the profile of the teeth being worn.

From the test I realised on the following fact. When the gearbox
handle is in the neutral position (not engaged to low nor direct
speed) the tight fit of the new bearing together with the oil shearing
resistance makes the sliding gear to rotate at a good speed, driving
the long gear and the toolholder. Surprisingly, in this position no
noise is produced. From this observation I conduced the following
test:

1. Run the gearbox without idle shaft in direct speed. Rattling is
   clear.
   
   {{< youtube id="Rkf4PtcnP9Q" >}}

2. Run the gearbox in the last conditions but the handle is in
   the neutral position. There is no noise.
   
   {{< youtube id="CNOvb7MLRtk" >}}

3. Run the gearbox in the last conditions. Begin with the handle in a
   direct position but carefully move it until the dog clutch is only
   slightly engaged. When engaged but very slightly, there is no noise
   too.  
   
   {{< youtube id="L6Y9HR-3nxk" >}}

So, my last conclusion is that maybe the clutch fitting is so tight that
slightly forces the alignment of the sliding gear in a way that makes
noise. This could explain too a couple of things:

1. The (maybe) original peening over the clutch, that maybe tells us
   that the clutch fitting is a sensible point in this gear train.
2. The fact that Schaublin sells together the main shaft and the
   sliding gear as a single spare. This seems to suggest that this
   assembly is best replaced together.


# Check the sliding gear #

The sliding gear (SG) seems to be in the centre of the noise
issues. Thus, I decided to spend some time checking the geometry of
this part. That's not an easy task given my set of measuring tools but
let's try it.

## Teeth contact pattern

First, the teeth where painted and then the gearbox but the idle shaft
S3 mounted again. After running during a short time, the printed
contact on the gear teeth can be seen. The next pictures show it. I
noticed no flaws in the contact pattern: well distributed along all
the tooth face without singular contact points.

{{< figure src="contacte-davant-1.jpg" >}}
{{< figure src="contacte-davant-2.jpg" >}}
{{< figure src="contacte-davant-3.jpg" >}}

The gear was running in a single direction. Thus, the non-contact face
of the teeth should show no contact points. From the following picture
it seems that there is no contact as expected. However, a small line
trace can be seen which I guess it is the result of an impact. This
would confirm that the noise can be classified as «rattle».

{{< figure src="contacte-darrera-1.jpg" >}}

In the previous pictures it is clear the condition of the teeth. Is
seems that there is not significant wear. The top land of the teeth is
in pristine state with no dents or burrs induced by wear.


## Gear eccentricity

The next test has been to check the eccentricity of the gear with
respect to the bearing. Because I wanted to measure over the tooth
surface instead of measuring over the top land, I ended using the
precision blocks tooling with a suitable diameter pin. The pictures
below show the tooling and the measuring way. The result was a very
good eccentricity with an approximate deviation under 0,01mm.

{{< figure src="excentricitat-engranatge-1.jpg" >}}
{{< figure src="excentricitat-engranatge-2.jpg" >}}


## Dog clutch eccentricity

I also tested the eccentricity of the female spline of the dog
clutch. Remember that it shows marks of have being hammered. I used an
approach not unlike the last one. However, in this case I measured the
play for every diameter using an indicator. I discovered some
eccentricity that at most amounts 0,04mm. The next pictures illustrate
this procedure.

{{< figure src="excentricitat-clutch.jpg" >}}

It is not clear to me how this eccentricity could influence the noise
generation. It must be some clearance between the female and the male
part of the clutch and this clearance could compensate this
eccentricity.


## Sliding gear play over the shaft

I practised also some tests of the sliding SG gear on the shaft
MS. The goal is to observe if when I connect the clutch there is any
misalignment of the gear. The next video shows how this is done. With
the indicator attached to the sliding gear and measuring over the
shaft, I moved the sliding gear in a rocketing movement while measure
the play. I have done this in a free position and also with the clutch
connected. You should take into account that there is an amplification
of the play measured because of the position of the indicator. Some
results are: (1) the play when free is about 20-30µm, which is right
enough given the tolerances that Schaublin exhibit in the drawings;
(2) the play is reduced when the clutch is connected but still there
is a play of about 10µm. This do not depends on the relative position
of the clutch.

{{< youtube id="lRqddtBRkDo" >}}


## Bearing diameter

Just to have all the data, I checked again the diameter of the
bearing in three distinct depths. The results go from 30.005 mm to
30.010mm, which is on the low range of it's tolerance class. The
pictures below show this.

{{< figure src="diam-engr-1.jpg" >}}
{{< figure src="diam-engr-2.jpg" >}}
{{< figure src="diam-engr-3.jpg" >}}


# Reading... and trying to understand

Being myself in a cul-de-sac, I tryed to break it by reading on gears
extensively. In parallel, together with my colleague Jordi Bonet, we
started to analyse the sound produced by the gears applying signal
processing techniques. 

The bibliography search conduced me to a paper of Rigaud and
Perret-Liauded entitled «Investigation of gear rattle noise including
visualization of vibro-impact regimes» in the Journal of Sound and
Vibrations
([doi:10.1016/jsv.2019.115026](https://doi.org/10.1016/j.jsv.2019.115026)).
This paper allowed me a deeper understanding of the
physical/mechanical nature of the rattle in gears and pointed me to
other papers also interesting.

An important progress was to confirm that the main cause of rattle is
the velocity fluctuation of the drive system. The conditions that can
influence on rattle noise are (a) the inertia of output gear; (b) the
drag torque; (c) the backlash; and (d) the lubrication.

In the SV13, the conditions (a), (b); and (d) are unchanged from the
initial design of the machine. Backlash, however, could have been be
modified at least two reasons:

1. Teeth are worn by some reason
2. Center to center distance between gears have changed (for instance
   because bearings are worn out or shafts bent).

Given that option (2) does not apply, only option (1) could be the
cause. However, as explained in the last section, the inspection of
the gear do not shows evidences of being worn. Indeed, the contact
patterns exhibit a good condition. Then, some wear must exist as
usual, but it seems not to be enough to be considered. It would be
interesting to have the annotated original drawing of the gear to try
to compare measures and get an analytical measure of wear if
possible. [Schaublin service](https://www.schaublin.ch), has declined
to make public this info considering it's a part still «in
production».

All this reasoning conduced me to think in a single important cause:
the velocity fluctuation of the drive system, that is the Reeves
variable speed driver of the machine.



<!--
{{< image classes="fig-100 center clear" src="original.jpg" >}}

{{< youtube id="k38Vl8QqrZE" >}}
-->
