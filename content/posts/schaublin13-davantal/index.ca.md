---
title: "Schaublin 13: consola"
slug: sv13-ref-6
date: 2022-11-30T18:00:00
coverImage: "sense-carro-x.jpg"
tags:
- schaublin-13
categories:
- restauració de màquines
- schaublin 13
keywords:
- Fresadora
- Schaublin 13
- Avenç automàtic
- Guies
draft: false
---

En aquesta entrada comento el desmuntat de la consol de la fresadora i
l'estructura dels mecanismes d'avenç automàtic. En especial el bloc
d'engranatges que alimenta els avenços i l'embragatge de seguretat.

<!--more-->

# Treure el carro X

La primera tasca consisteix a treure el carro X. Només cal afluixar la
grapa que prem la femella del cargol d'avançament, treure la caixa de
la maneta de l'esquerra i treure d'una tirada tot el cargol
d'avançament per l'esquerra.

{{< figure src="cargol-1" >}}

{{< figure src="cargol-2" >}}

Ara es pot treure el carro afluixant el regle i amb l'ajuda del
ternal:

{{< figure src="treure-carro-x" >}}


# Alguns elements de la consola

Amb el carro fora, desmuntem alguns elements de la consola. Se separa
la caixa de la maneta d'avenços per que no faci nosa. També la tapa de
l'embragatge de seguretat, que deixa al descobert la transmissió dels
avenços (a la dreta, l'embragament):

{{< figure src="transmissio-avencos" >}}

També es treu la tapa frontal d'alumini que protegeix els engranatges
interns dels avenços. És interessant per que la tapa conté part del
circuït de lubricació centralitzada de la consola:

{{< figure src="tapa-frontal" >}}

{{< figure src="lubricacio-frontal" >}}

El següent pas és treure la consola sencera amb el ternal. Surt sense
massa problemes:

{{< figure src="sortida-davantal-1" >}}

{{< figure src="sortida-davantal-2" >}}

Cal anar acompanyant amb l'avenç Z i anar amb compte amb l'arbre dels
avenços que surt de la caixa dels avenços que hi ha a la safata.


# La caixa dels avenços

A la safata de la màquina hi ha una caixa amb forma de cilindre que
cobreix alguns engranatges dels avenços. A més del canvi de direcció
(de horitzontal a vertical), aquest bloc d'engranatges garanteix:

1. Un sentit de gir de l'arbre de transmissió sempre igual
   independentment de com gira el motor.
2. La prioritat de gir pel motor d'avenços ràpids

Essencialment s'aconsegueix amb un mecanisme enginyós: uns engranatges
muntats sobre uns cadells de corrons amb sentit de gir oposat.

{{< figure src="caixa-avencos" >}}

{{< figure src="caixa-avencos-2" >}}

{{< figure src="eng-avencos" >}}

Es reposen la junta v-ring i les tòriques del circuït de lubricació.


# La transmissió dels avenços

La potència pels avenços arriba a la taula per una barra que mou un
parell d'engranatges el darrer dels quals és solidari amb un visenfí
que transmet el moviment als mecanismes interns de la
consola. Seguidament es pot veure tant desmuntat com muntat el paquet
format pels coixinets i el primer engranatge del sistema. El paquet es
fixa amb un vis sobre els anells separadors dels coixinets.

{{< figure src="primer-eng-1" >}}

{{< figure src="primer-eng-2" >}}

El segon engranatge està muntat sobre un embragatge de seguretat i és
solidari amb un visenfí.

{{< figure src="segon-eng-1" >}}

L'embragatge de seguretat es basa en un seguit de boles pressionades
per molles que, generalment, volten solidàries amb l'engranatge però
que poden lliscar sorollosament si s'excedeix el parell pel que està
dissenyat. La següent imatge mostra el mecanisme explosionat:

{{< figure src="segon-eng-2" >}}

És interessant notar el fet que l'eix és foradat i el travessa una
metxa de llana crua per la qual ascendeix l'oli que es diposita en al
zona del fons de l'eix. La idea és que mantingui la lubricació per
capilaritat. No és gens evident la efectivitat del disseny. Les
referències sobre engreixadors per capil·laritat donen una capacitat
d'ascensió d'uns 40mm, que és pobra per la llargada de l'eix. Per
substituïr la metxa, s'han buscat metxes de llana no tractada
específica per a engreixadors per capil·laritat. Se n'han trobat a
[Heritage steam
supplies](https://www.heritagesteamsupplies.co.uk/worsted-wool-lubricator-kit.html).

El muntatge de l'embragatge després de netejar-lo, que semblava
delicat, no ha suposat massa complicacions:

{{< figure src="muntatge-eng-1" >}}


# Desmuntar el nonius de l'eix Z

El paquet del nonius i la maneta de l'eix Z és sofisticat. Per
facilitar el desmuntatge amb l'extractor ens hem ajudat d'un parell de
brides de cremallera i un topall com mostren les següents fotos:

{{< figure src="brides-1" >}}

{{< figure src="brides-2" >}}

{{< figure src="brides-3" >}}

En la següent foto es veu el coixinet del nònius i el fiador amb la
molla de pressió:

{{< figure src="fiador-nonius" >}}

Finalment es pot observar l'explosionat del bloc del nònius. Ben
sofisticat per ser un nònius:

{{< figure src="peces-nonius" >}}


# La palanca de comandament

La palanca que serveis per comandar els avenços és un mecanisme
enginyós tancant dins d'una caixa i connectat als diferents
embragatges almenats de la consola. Dins la caixa, un sistema
transforma els moviments de la palanca en rotacions parcials
d'engranatges que serviran per moure els embragatges interns. A més,
el mecanisme evita que es puguin activar simultàniament els dos
avenços (Z i X) i implementa els topalls de seguretat que desconnecten
la marxa si s'arriba al final de carrera. Es neteja i lubrica de nou
tot el mecanisme:

{{< figure src="palanca-1" >}}

{{< figure src="palanca-2" >}}

{{< figure src="palanca-3" >}}
