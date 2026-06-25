---
title: "Microscopi de mesura Zeiss"
slug: zeiss-tm-micro
date: 2026-04-12
coverImage: "rosca-iso.webp"
tags:
- tech.pintura
- tech.tornejat
- tech.fresat
- tech.mesura
- eines
categories:
- biblioteca
- projectes
- màquines venudes
- eines
# bi-nivells (primer item obligat)
- restauració de màquines
- boley leinen LZ4SB
- schaublin 13
- uniz hacksaw
- wörner B13
- altres
keywords:
- microscopi de mesura zeiss
- microscopi de mecànic zeiss
- greix esmorteïdor
draft: true
---

El microscopi de mesura Zeiss és una eina versàtil per a mesurar les
més diverses peces mecàniques de mida petita i mitjana. És un
dispositiu híbrid en el que les mides es prenen tant mecànicament com
òpticament. Es van començar a fabricar cap a principis del segle XX i
es van dexar de fabricar cap els anys 1970. En aquesta entrada es
documenta com es posa a punt un d'aquests microscopis, fabricat a
l'Alemanya de l'Est, en bones condicions però amb un manteniment
deficient.

<!--more-->

# El microscopi i els seus accessoris

El microscopi de mesura gran de Carl Zeiss (Große
Werkzeugmikroskop-GWM) és un aparell de mesura de precissió per a
peces petites i mitjanes. El seu funcionament principal fa servir el
microscopi per al posicionament precís de la peça i mesura les
caraterístiques emprant una taula XY ---que es desplaça emprant
micròmetres--- i una taula rotativa graduada de 6' en
6'. Complementàriament, també es pot fer servir el microscopi com a
element de mesura (i no de posicionat). En aquest cas, es fan servir
oculars específics que permeten diferents tipus de mesures: angles,
perfils i distàncies. Quan s'usa l'ocular es projecta una imatge
precisa de l'objecte en un pla concret de l'ocular. En aquest pla, hi
ha grabades escales, perfils o altres elements que faciliten la
mesura.

{{< figure src="microscopi-1.webp" 
    caption="Microscopi amb el palpador òptic muntat" 
>}}

Com es veu a la figura anterior, el microscopi el conforma una base
sòlida sobre la que es munta una taula XY desplaçada per
micròmetres. Sobre la taula cartesiana, una taula giratòria. La base
també suporta un tub de microscopi amb objectius intercanviables i
oculars dotats de graella de mesura també intercanviables. A la
fotografia anterior hi ha muntat un ocular goniomètric i un palpador
òptic superposat a l'objectiu.

Algunes imatges de detall:

{{< figure src="tub-microscopi" 
           caption=`El tub del miscrocopi. A la part de baix l'anell d'enfocament 
		            fi de l'objectiu. A la part de dalt l'ocular goniomètric amb el 
					seu petit microscopi per a llegir l'angle.`
					>}}

{{< figure src="taula" 
           caption=`La taula XY. S'hi veuen les guies Y i el micròmetre de desplaçament
		   en la direcció Y. També es veu la taula rotativa amb el nònius de mesura de l'angle.`
           >}}

Acompanyen al microscopi un conjunt extens d'accessoris que amplien i
complementen la seva funcionalitat. Es podrien dividir en:
* Accessoris de suport pels espècimens a mesurar.
* Objectius de diferents graduacions.
* Oculars per a mesurar formes específiques.
* Epi-il·luminador (també de camp fosc) per treballar amb llum reflectida.
* Palpador de mesura òptic.
* Centrador de coincidència per a localitzar forats i altres característiques.


# El manual

El manual del microscopi circula per la xarxa en diverses versions,
totes elles en alemany. Les diferents versions de manual corresponen a
diferents versions del microscopi, que s'ha fabricat durant uns 70
anys. Per aquest tipus d'instrument, el manual és important: s'hi
consignen detalls específics del seu ús correcte però també dades
sobre la incertesa de les diverses mesures i altres informacions
rellevants.

Aquesta rellevancia m'ha dut a fer una tasca de traducció cap a
l'anglès per deixar en obert. La traducció s'ha fet amb el suport
d'eines automàtiques i la composició s'ha fet amb
[LaTeX](https://www.latex-project.org/), que ha permes un resultat de
gran qualitat.

* Manual en mida A4
* Manual en mida A5 compaginat per imprimir i enquadernar en llibrets


# Estat del microscopi

El microscopi està en bon estat, no sembla que hagi tingut un mal us a
primera vista. No és clar si ha tingut poc o molt ús. Per l'estat
d'alguns caps de cargol alguna vegada s'ha desmuntat, segurament per
fer manteniment. El problema principal que pateix rau en la
solidificació dels greixos lubricants originals. Aquest és un problema
típic dels instruments de precissió fabricats sota l'òrbita soviètica
(i potser altres també): la durabilitat dels greixos lubricants és
finita i es degraden formant un engrut extremadament enganxós o, fins
i tot, una mena de laca dura que acaba bloquejant tots els
mecanismes. De tots els mecanismes lliscants del microscopi, només les
taules XY i la guia Z del microscopi es mouen amb certa
llibertat. Resten bloquejats:

* Els micròmetres
* El tub del microscopi (per a l'ajustat fi del focus)
* El mecanisme d'inclinar l'eix Z del microscopi
* La taula rotativa
* El botó de fixació de la taula rotativa
  
Alguns dels accessoris també pateixen els mateixos problemes però
aquests es tractaran en un altre nota.

L'altre problema rellevant és la obsolescència del sistema
d'enllumenat. A més de que el microscopi es va comprar sense la font
d'alimentació original, està dissenyat per a fer servir bombetes
hal·lògenes «de precissió» ---que ara mateix són difícils
d'aconseguir--- i tenen una vida útil afitada. Fóra interessant,
doncs, actualitzar el sistema d'il·luminació a tecnologia lED.


# Treballs de reconstrucció

## El greix solidificat

Aquest problema és motiu de debat habitual en els fòrums de
microscoscopia i restauració d'aparells de precissió. Per exemple,
vegeu la sèrie d'articles d'Ian Walker a «Microscopy.uk» sobre la
restauració d'un microscopi LOMO:

* [Notes on refurbishing and the use of Nye special
  lubricants](http://www.microscopy-uk.org.uk/mag/indexmag.html?http://www.microscopy-uk.org.uk/mag/artmar06/iw-lomooblique.html)
* [Notes on refurbishing seized rotating
  stages](http://www.microscopy-uk.org.uk/mag/indexmag.html?http://www.microscopy-uk.org.uk/mag/artmar06/iw-lomooblique.html)
* [Notes on refurbishing the oblique condenser and condenser
  diaphragm.](http://www.microscopy-uk.org.uk/mag/indexmag.html?http://www.microscopy-uk.org.uk/mag/artmar06/iw-lomooblique.html)

En el cas dels aparells òptics, aquest problema és especialment
empipador. La presència de lens ---potser amb recobriments---, que són
delicades a nivell mecànic i químic i que no admeten la brutícia,
dificulten els mètodes més habituals de neteja, que sovint passen per
la immersió en banys de productes dissolvents o l'aplicació de
calor. Un problema afegit és el dels acabats cosmètics i les marques i
grabats en escales.  Cal, doncs, actuar amb extrema suavitat i tacte
en la neteja. No hi ha una recepta universal sinó una tècnica concreta
per a cada situació.



La regla fonamental és aplicar les tècniques més suaus possibles i
incrementar l'agressivitat només si és imprescindible. Per exemple, en
el cas de productes dissolvents, la seqüència (de menys a més) podria
ser alcohol isopropílic--white spirit--acetona. Pero no és
generalitzable! en algunes laques poden ser sensibles a l'alcohol i no
pel white spirit, per exemple. Sempre és prudent provar amb cura
abans.

## Greix esmorteïdor

Tothom recorda la sensació tàctil de precissió i suavitat dels
mecanismes d'enfocament dels objectius de qualitat de les càmeres
analògiques. Més enllà de la precisió amb que ajusten les rosques que
mouen els objectius, el gran secret és el greix esmorteïdor: greix
lubricant d'alta viscositat que s'utilitza en enginyeria i mecànica
per reduir el soroll, les vibracions i per donar una sensació de
resistència «suau» i controlada en components mòbils. Són tipicament
els greixos emprats en potenciòmetres, càmeres, tubs optics i, en
viscositats més elevades, tapes de descens suau en mobiliari.

En el cas que ens ocupa, són imprescindibles per lubricar els tubs
òptics i altres mecanismes que volen un tacte suau i delicat, com ara
la taula circular.

En tot el projecte s'han fet servir els greixos sintètics Tribosyn 320
comprats a [NewgateSimms](https://newgatesimms.com). Es interessant el
«Damping Grease Trial Pack», que permet adquirir una petita quantitat
---però suficient--- de diferents viscositats. 

{{< figure src="tribosyn-320.webp" >}}

Les viscositats emprades són més aviat les lleugeres. Depèn del
mecanisme i la seva funció s'han triat viscositats més grans o més
petites.

## Neteja del vidre òptic




## Eines especials





<!--
{{< figure src="original.jpg" loading="lazy">}}

{{< youtube k38Vl8QqrZE >}}
-->
