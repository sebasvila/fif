---
title: "Kaiser Piccolo Boring Head Repair"
slug: kaiser-piccolo-repair
date: 2024-10-14
coverImage: "head-4.jpg"
tags:
- tech.turning
- tech.milling
- tech.measuring
- leinen-lz4sb
- schaublin-13
- wörner-b13
- tools

categories:
- projects

keywords:
- Kaiser Piccolo
- boring head
- automatic facing
- diacator
draft: true
---


The Kaiser Piccolo is exquisitely made small boring head with boring
and automatic facing functions. I got a ISO30 one in a very nice
condition together with a bunch of tooling. When tested it performed
very fine but I couldn't switch easily between facing and boring
(marked as P and A in the head, maybe for the french «planage» and
«alésage»). It needs to be serviced to cope with this jam.

<!--more-->

{{< toc >}}

## The Kaiser Piccolo boring head

The Kaiser boring head is a middle size boring head with a facing and
boring range from 2mm to 180mm. The slide travel is about 30mm
maximum. It has three functions:

- boring, with a minimum diameter adjusting step of 0,005 mm
- facing, where the slide has an automatic feed of 0,05 mm per
  revolution
- fast slide return, where the slide return automatically at 2,5mm per
  revolution
  
The head has a friction clutch that limits the slide and allows the
slide displacement be limited by stops.

I know of two versions of the head. The old version could be easily
recognized by its small rotary switch between boring and facing
functions. I own a new version one with an STP shank. This is a Kaiser
specific shank used as an interface to other standard shanks. In this
case it mounts an ISO 30 shank.

{{< figure src="head-1.jpg"
	loading="lazy"
	title="A picture of the Kaiser Piccolo boring head" >}}

{{< figure src="head-3.jpg"
	loading="lazy"
	title="Detail of the Kaiser Piccolo boring head" >}}



## The Boring Head P-A Switch is Locked 

My boring head looks like the P-A switching ring is locked into A
position. That's suprising because the head is nicely used and seems
not abused at all. However, after fighting with the ring during days
the result is clear: the ring is locked.

The head should be serviced to solve this lock.

## How to Take Kaiser Piccolo Apart?

The first challenge is to take apart the head. After a search in some
forums and a fruitful talk with a XX, the mistery was discovered: head
should be taken apart by untighting a special flat nut that is on top
of the head.

First, then, the ISO 30 shank should be removed from the STP
taper. This is easy to do by just tightening the ISO 30 shank in the
vice and unscrewing all the head. It's useful to slightly heat the ISO
30 shank. Take an adjusting wrench of a nice size and adjust it to the
head slide. Unscrew counterclockwise. It is tight, but a large
enough wrench will do the job.

Under the ISO 30 adaptor will appear a flat nut with three small
holes. This is the nut that frees all the boring head interior
parts. The holes are filled with a pin that retain the nut on the part
below. These pins should be completelly drilled and removed. You will
need an extralarge drill or an home made extension.

{{< figure src="forat-fiador-1.jpg"
	link="forat-fiador-1.jpg"
	loading="lazy"
	title="Drilling the boring head nut pins" >}}

The boring diameter is 1,5mm and should be drilled about 6mm
depth. Sometimes, a smaller diameter drill of about 1,25mm could be
useful too. The objective is to completely remove the pins. You will
feel when the drill impacts on the hard part in the bottom. Be gentle
with this and try not to mark the bottom part with the drill.

{{< figure src="forat-fiador-2.jpg"
	loading="lazy"
	title="Detail of a pin drilling process" >}}

{{< figure src="forat-allargador.jpg"
	loading="lazy"
	title="Working a drill extension in the milling machine" >}}


## Make the Special Pin Wrench

Once pins are removed, you will need a special wrench to unscrew it. I
made one from an aluminium ring and some cuts of clockmaker blue steel
(tamponstahl).

First step is to measure the precise holes position. If you assume
that they are in the same circle and that all of them are at an angle
of 120 degrees, you only need to measure the distance between
holes. Using a couple of drills as reference pins the distance could
be measured with a caliper or a micrometer. After that, a bit of
trigonometry will do the job.

{{< figure src="mesura-cc.jpg"
	loading="lazy"
	title="Measuring the distance between holes using drills" >}}
	
{{< figure src="calcul.jpg"
	loading="lazy"
	title="Calculation of special wrench main distances" >}}

The result is that the centers of the pin holes are on a 30mm circle
centered on the head shaft. With this in mind, I turned a kind of
thick ring of aluminium. On this, three 1,5mm where drilled
through using a divider on the Schaublin 13.

{{< figure src="centrant-clau-2.jpg"
	loading="lazy"
	title="Align the part center using the Diacator alignment gauge" >}}

{{< figure src="centrant-clau-1.jpg"
	loading="lazy"
	title="A detail of the alignment process" >}}

{{< figure src="puntejant.jpg"
	loading="lazy"
	title="Spot the drilling points of the wrench" >}}
	
{{< figure src="foradant.jpg"
	loading="lazy"
	title="Drill the wrench pin holes" >}}
	
Once the ring is drilled, cut some long pins of clockmaker's blue
steel of 1,5mm. This kind of small steel bars used by clockmakers is
of good quality, easy to find in small batches and hardened at an
interesting level: it is hard but can be worked well enough. Pins need
to protrude the ring about 4mm. They could be fixed in the ring with a
bit of cyanoacrylate glue.

{{< figure src="clau-1.jpg"
	loading="lazy"
	title="The special wrench for Kaiser Piccolo (nut side)" >}}

If the wrench fits the nut, drill on the oposite side some 4mm holes
to be turned with a standard pin wrench. Next picture shows
it. Remember that pin wrench should then't be in contact with the STP
cone of the head.

{{< figure src="clau-2.jpg"
	loading="lazy"
	title="The special wrench for Kaiser Piccolo (top side)" >}}


## Take Apart the Boring Head

Now the Kaiser Piccolo head can be taken apart. It is usefull to mark
the original position of the nut to be tightened appropiately when
mounted again. Then, just grip it on the vice and unscrew slighty the
top nut until can be turned by hand. 

{{< alert warning >}}
Do not unscrew the nut completely! Inside the head there are a 
couple of ball bearings that will fall off when you unscrew it.
{{< /alert >}}

It's very interesting to work on the head maintaining it in a plastic
container that avoids losing balls. With this care, just unscrew the
nut and the head rings will be freeded and the top bearing will
appear. Preserve the steel balls in a secure container using
tweezers. There are 54 balls of 2mm.

{{< figure src="femella-superior.jpg"
	loading="lazy"
	title="The unscrewed nut and the top bearing" >}}

Once the top ring has been pulled apart, the top part of the second
ring will appear. This is the ring that can be holded with a stick
when working. Two distinct balls will appear. Both measure 2,5mm and
are a bit greather than the bearing ones. The first one is a sliding
ball on top of the clutch shaft (marked A) in the next figure. The
second one is a spring and ball plunger that retains the top ring in a
specific position (marked B).

{{< figure src="rodament-superior.jpg"
	loading="lazy"
	title="Top of second ring" 
	caption=`Marked as (A) there is the clutch shaft. Marked as (B) 
	         is the top ring plunger spring.` >}}

The second ring is easy to pull apart. Just pull it through the
shank. You will discover the internal gears that move the slide in
automatic mode. On the bottom of this ring there is the bottom ball
bearing, be careful. This bearing is composed by 90 balls of 2mm.

{{< figure src="anell-pinyons.jpg"
	loading="lazy"
	title="Bottom of the second ring" >}}

{{< figure src="rodament-inferior.jpg"
	loading="lazy"
	title="The head after pulling the second ring" 
	caption=`In the left, there is the second ring. In the right you
	can see the bottom bearing and the two central gears. The top one
	is attached to the shaft by a small key. Note the small hole that
	is used to lock the top nut by inserting the pins. The bottom
	gear, barely visible under the top gear, is attached to the third
	ring and turns freely. `>}}
	
If you pull with care the third ring, you will discover the interior
gear that rotates the main gear of the head. The main gear of the head
displaces the slide. Look at the pictures below.

{{< figure src="anell-inferior.jpg"
	loading="lazy"
	title="The third ring"
	caption=`In the interior you can apreciate an internal gear that
	engages the main gear. Main gear can be barely seen in top right.`>}}

{{< figure src="conjunt.jpg"
	loading="lazy"
	title="The Kaiser Piccolo fully dismantled" >}}

{{< figure src="engranatge-carro.jpg"
	loading="lazy"
	title="A detail of the main gear" 
	caption=`This gear is moved by the third ring and it moves the
	head slide.` >}}
	
{{< figure src="guia-portaeines.jpg"
	loading="lazy"
	title="The main gear where it engages the head slide" >}}

{{< figure src="portaeines.jpg"
	loading="lazy"
	title="The hidden face of the slide where the main gear engages" 
	caption=`Note that the main gear is composed by distinct diameter
	gears in the same assembly. Only the minor lateral gears move the
	slide. The major gear is moved by the third ring.`
	>}}

## Solving the Kaiser Piccolo Jam

Finally, it is time to solve the boring head jam. After taking apart
all the head I saw no problems that could explain the jam. I mounted
it again and the head became locked again. I did the work of
assembling and disassembling several times with the same result. At
the end, I deduced that the locking effect should be produced by the
plunger mechanism. The plunger ball has a diameter of 2,5mm while the
spring hole measures 3,1mm. Seems to me the ball is displaced to a
side of the hole when turning the top ring and it gets trapped in some
way. That is weird because the ball seems to be the original one. I
tested with a 3mm ball and all worked smooth as silk!

Remains the question about which is the right diameter for the plunger
ball and, if 2,5mm is wrong, why is there a 2,5mm ball? Anyway, now it
is working as expected.

All the rings and bearings were assembled again and the nut tightened
to the mark we made before taking it apart. Then, a single pin is
introduced in the single locking hole. The pin is made of brass to
make easy drilling it again if needed.


## How Does The Head Work

## Interesting References
