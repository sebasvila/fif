---
title: "Schaublin 13: carro longitudinal"
slug: sv13-lslide
date: 2023-09-26T19:17:09+02:00
coverImage: "long-slide-grinded.jpg"
tags:
 - tech.tornejat
 - tech.mesura
 - tech.rasquetat
 - schaublin-13
categories:
 - restauració de màquines
    - schaublin 13
keywords:
 - Schaublin 13
 - Reconstrucció de la geometria
 - Rasquetat de les guies
draft: false
---

En aquest post s'explica com es va comprovar el carro longitudinal i
com es va refer les seves guies.

<!--more-->

# Anàlisi del desgast

La primera inspecció ocular del carro va evidenciar que no hi havia un
desgast excessiu. La majoria de plans mostraven les marques del
rectificat d'una forma consistent com es pot veure a la següent foto:

{{< image classes="fig-100 center clear" src="long-slide-grinded.jpg"
>}}

Aquesta textura de rectificat és d'allò més interessant. Sembla que
substitueix les superfícies rasquetejades en molta màquinària de
qualitat després dels anys 70 del segle anterior. En una conversa amb
Oriol Morató (https://www.instagram.com/mecanicadeprecisio) vam
concloure que es podria tractar d'un rectificat fi seguit d'un
rectificat bast que només ratlla el pla rectificat però no n'altera
la geometria. En la nostra opinió, el ratllat actua de reservori d'oli
i obté propietats similars a les del rasquetat. Potser algun lector té
informació més detallada sobre aquest punt i pot confirmar-ho o no.

Els plans interns no són tant fàcils d'observar, però una comprovació
amb els regles i la tinta blava mostra que hi ha molt poc
desgast. També es va comprovar el paral·lelisme de les cares petites
de l'oronella amb l'utillatge de la següent fotografia i un
comparador. El resultat va mostrar un molt bon paral·lelisme.

{{< image classes="fig-100 center clear" src="mesura-paral.jpg" >}}

L'última prova que es va fer va ser comprovar el paral·lelisme entre
el pla de treball i els plans de la guia. Això es va fer posant el
carro sobre marbre de mesura com podeu veure a la imatge següent.

{{< image classes="fig-100 center clear" src="on-surface.jpg" >}}

Aquesta prova va concloure que el pla de treball i la guia són
paral·les. També es va descobrir que el pla superior de la guia és més
o menys 3μm més baixa. Això és coherent amb la inclinació preferida de
la taula de treball de la fresadora: lleugerament més alta a la part
frontal, per compensar la càrrega de l'utillatge que suporta.

{{< image classes="fig-100 center clear" src="mesures-taula.jpg" >}}

Amb tota la informació vaig decidir ser conservador i no alterar el
carro longitudinal. Si fos necessari, seria fàcil modificar el carro
en el futur, ja que hi ha poca feina per desmuntar-lo.

Un altre assumpte és la part fixa en el davantal que suporten el
carro. En aquest cas, una simple prova amb el regle revela un desgast
significatiu a la part superior. A la part de baix hi ha el regle
d'ajustat, que vaig suposar que també estava gastat porta. El patró de
desgast és més pronunciat en els extrems, que és raonable.

Primer em vaig centrar en la guia superior. Inspeccionant
detingudament el patró de desgast es veu més pronunciat als costats i,
alhora, a la part superior del camí. El següent dibuix esbossa aquesta
circumstància. En aquest dibuix, la zona ratllada en verd, mostra
la zona desgastada.

{{< image classes="fig-100 center clear" src="desgast-guia.jpg" >}}

Aquest patró de desgast és coherent amb els esforços del treball
habitual.

Per entendre millor com es relacionen les càrregues amb el desgast,
mireu el següents dibuixos.

{{< image classes="fig-100 center clear" src="causa-desgast.jpg" >}}

A l'esquerra (vista frontal) el petit rectangle representa la guia
fixa del carro longitudinal. El carro pròpiamnet s'ha dibuixat com un
rectangle llarg. Com la càrrega sobre la taula (inclos el pes de la
mateixa taula) sol estar descentrat, el desgast s'accentua en les
cantonades de les guies fixes com es mostra en verd.  Al dibuix de la
dreta (vista lateral) hi la guia fixa de la taula + el carro + la
taula. La càrrega i el pes de la taula tenen tendència a desgastar la
part superior de la guia fixa, que es mostra en verd.


# Resparació del desgast

Per a reparar el desgast s'ha començat rasquetant la cara superior de
la guia fixa. La guia principal la dona el regle amb el blau. Cal anar
amb compte a no alterar la perpendicularitat respecte l'eix Z. La
comprovació d'aquesta perpendicularitat no és senzilla i per tant cal
ser curós.

Una vegada la guia superior ha recuperat la planitud, ens dediquem al
regle d'ajustatge de la part inferior. En aquest cas, comprovar
l'ajustament és complicat. S'opta per muntar el carro i emprar una
palanca per forçar un moviment de balanceig que permeti intuïr el
ajustat del regle. La següent fotografia mostra el muntatge:

{{< image classes="fig-100 center clear" src="palanca.jpg" >}}

El comparador mesura el balanceig al final de la guia. Simulem la
càrrega de la taula amb el propis pes ajudats del braç de palanca. Amb
això és fàcil determinar si el regle d'ajustat té bon contacte. Es
retoca fins que el balanceig mesurat està per sota de les 10µm, potser
al voltant de 5 a 7 µm. Cal tenir present que amb càrregues importants
també la capa d'oli es premsa.

Les cares planes de la guia estàtica no s'han modificat. La inspecció
va concloure que tenien molt poc desgast. Seguint el principi
conservador que ha guiat aquesta reconstrucció es va decidir no
alterar-les. També cal esmentar que les cares estretes de la guia van
ser rasquetades un pèl més fondes en el centre. En un post futur
parlaré d'aquesta estratègia de rasquetat.

# Tornem a muntar

Després d'ajustar la geometria, muntem de nou el carro i tots els
annexes. Els nònius d'esquerra i dreta es van netejar completament i
els rodaments es van lubricar de nou amb greix «Kluber LDS Special A»
com indica el manual. Al desmuntar el nonius de l'esquerra, el fiador
va apareixer trencat. Se'n va fer un de nou, del radi apropiat i amb
el tremp escaient. La darrera foto ensenya el vell i el nou abans del
tractament tèrmic. En un post futur explicarem com es va tornejar el
radi precís sense utillatge de radis.

{{< image classes="fig-100 center clear" src="pin-2.jpg" >}}
