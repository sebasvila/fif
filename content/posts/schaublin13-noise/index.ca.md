---
title: "Schaublin 13: soroll d'engranatges"
slug: sv13-gearnoise
date: 2024-01-14
coverImage: "gear-train-1.jpg"
tags:
- tech.tornejat
- tech.mesura
- schaublin-13
categories:
- restauració de màquines
- schaublin 13
keywords:
- fresadora metall
- soroll canvi marxes
- soroll engranatge
- variador de velocitat
- tensió de la corretja
draft: false
---

Per alguna raó, des del principi de la restauració, vaig pensar que el
canvi de marxes estava en bon estat. De fet, no el vaig revisar ni
tant sols vaig buidar l'oli del càrter. Quan ha arribat el moment
d'engegar... el canvi feia un desagradable soroll en certes velocitats
:raised_eyebrow:

<!--more-->

# Context

El que segueix és una foto del tren d'engranatges en posició de «marxa
directa»:

{{< figure src="gear-train-1.jpg" >}} 

A la imatge, MS és l'eix principal sobre el que actua la corretja del
variador (a la dreta de l'eix segons la foto). Sobre MS llisca
l'engranatge SG. L'eix principal té un pinyó G2 que engrana
permanentment amb la corona S3. Al mateix temps, G2 fa d'embragatge
conjuntament amb SG: la part dreta de SG és una campana que engrana
amb G2 i fa que MS i SG voltin solidàriament. Aquesta és la posició
que es mostra a la fotografia. L'engranatge SG està permanentment
engranada a l'engranatge llarg que transmet la potència al capçal.

Seleccionem la marxa lenta fent lliscar SG cap a l'esquerra. Llavors
SG engrana amb el pinyó de l'eix S3. La següent fotografia mostra el
tren en marxa lenta:

{{< figure src="gear-train-2.jpg" >}} 

Addicionalment, hi ha una posició intermèdia de SG en que no engrana
amb cap pinyó i gira lliurement sobre el seu eix. En aquesta posició,
l'engranantge llarg G1 esdevé desconnectat de l'eix principal.

Després de buidar l'oli i desmuntar la caixa de canvis, s'ha
descobert el següent:

1. El coixinet de bronze de l'engranatge lliscant SG està molt
   desgastat: uns 0,5 mm pel costat de l'engranatge i 0,1 mm per la
   banda de la campana de l'embragatge.
2. Els rodaments semblen en prou bon estat. El coixinet de boles que
   suporta la tensió de la corretja te un pèl de joc però res massa
   important.
3. Els engranatge no tenen cap defecte evident. Semblen en molt bon
   estat. Fins i tot l'engranatge afectat pel desgast del coixinet
   aparenta bon estat.
4. Sembla que la caixa de canvis no havia estat mai oberta.
5. La campana de l'embragatge a l'engranatge lliscant te marques
   leugeres d'un martell de bola. Sembla com si hagues estat ajustada
   a cops de martell. És realment intrigant. És el resultat d'alguna
   reparacio maldestra? o potser una forma habitual d'ajustar el joc a
   can Schaublin?
   
    {{< figure src="dog-clutch.jpg" >}}
	
# La reparació del coixinet de bronze

Vaig preguntar a Schaublin sobre la possibilitat de canviar el grup de
l'engranantge lliscant. Van contestar que ara mateix no en tenien
recanvi tot i que no era inusual tenir-ne. També em van informar que
el recanvi el formava el grup de l'eix principal i l'engranantge
lliscant. El preu era alt però gens exagerat. Amablement em van enviar
el plànol del coixinet amb el dimensionat i toleràncies.

El plànol especifica el material com a bronze «Duralit 110» que deu
ser una referència d'un fabricant. No vaig trobar cap catàleg ni altra
documentació del fabricant però, indirectament, uns documents van
corroborar que és equivalent al bronze Rg7.

Es va tornejar un nou coixinet amb el dimensionat del plànol. Més
aviat en la zona ajustada dins la tolerància. Es substitueix el
coixinet i es munta de nou el canvi de marxes. Desafortunadament,
l'embragatge no entrava suau amb el nou coixinet i es va haver
d'ajustar de nou.

Els següents videos mostren moments del tornejat del nou coxinet i de
l'ajustat final de l'embragament.

{{< youtube id="RvptHNiNIQM" >}}

{{< youtube id="pCuSIBRZTgs" >}}

# El canvi fa soroll amb el nou coixinet

Després de muntar de nou en canvi i capgirar l'engranatge llarg per
engranant amb la part més nova.. engegem i fa un soroll de repic quan
s'engrana la marxa directa, un soroll més clar quan gira a poques
revolucions.

# Per què?

Començo una colla de proves per mirar d'entendre per què el canvi fa
soroll. Desmunto de nou la caixa de canvis, torno a capgirar
l'engranatge llarg, i munto de nou la caixa sense oli i sense l'eix
intermedi. Primer, mirem de saber on s'origina el soroll.

Amb aquesta configuració, és ben clar que el soroll es produeix entre
l'engranantge lliscant i l'engranantge llarg i només quan hi ha
engranada la marxa directa. Que només passi amb una marxa sembla que
indiqui que no te cap relació amb un possible desgast dels
engranantges (ja que són els mateixos en ambdues solucions).

De les proves s'observa el següent. Quan la palanca del canvi es posa
en marxa neutre (el canvi desconnecta el gir del portaeines),
l'engranatge lliscant gira arrosegat per la fricció de l'oli i
arrossega el portaienes. Sorprenentment, en aquesta situació no hi ha
soroll. Per entendre-ho millor es fan les següents proves:

1. S'engega amb el canvi en posició directa i sense l'eix
   intermedi. El soroll és ben clar:
   
   {{< youtube id="Rkf4PtcnP9Q" >}}
 
2. S'engega amb el canvi sense l'eix intermedi i amb la palanca en
   posició neutre. No hi ha soroll.
   
   {{< youtube id="CNOvb7MLRtk" >}}   
   
3. S'engega amb el canvi sense l'eix intermedi i amb la palanca en
   posició directe. Poc a poc es mou la palanca fins que l'embragatge
   està només lleugerament engranat. En aquesta posició no hi ha
   soroll.
   
   {{< youtube id="L6Y9HR-3nxk" >}}

D'aquestes proves semblaria deduir-se que potser quan s'embraga
l'engranatge es força una mica l'alineació i això indueix un mal
contacte entre dents que genera soroll. Això podria explicar també
que:

1. Els comps sobre la campana (potser originals) podríen indicar que
   l'ajust de l'embragament és una qüestió delicada.
2. El fet que Schaublin vengui conjuntament l'eix principal i
   l'engranatge lliscant podria suggerir també que aquest ajustatge
   és delicat.
   

# Comprovem l'engranatge lliscant

L'engranatge lliscant SG sembla ser el centre dels problemes de
soroll. Per tant, decideixo gastar esforços comprovant la geometria
d'aquesta peça. Potser amb les eines de mesura de que disposem no serà
fàcil però provem-ho.

## Contacte entre dents

Pintem les dents de l'engranatge lliscant i el muntem a la caixa sense
oli ni l'eix secundari. Després de funcionar un temps, es pot veure el
patró del contacte entre dents. Les següents fotografies mostren el
patró de contacte. En apariència no es veuen defectes: el contacte
està ben distribuït en la cara de la dent i no es veuen punts de
contacte singulars.

{{< figure src="contacte-davant-1.jpg" >}}
{{< figure src="contacte-davant-2.jpg" >}}
{{< figure src="contacte-davant-3.jpg" >}}

El test s'ha fet girant en una sola direcció. Per tant, la cara on no
hi ha contacte no hauria de mostrar cap contacte. La següent imatge no
delata cap contacte, però s'hi veu una línia al llarg de la cara que
sembla resultat d'un impacte i el conseqüent rebot. Si fos així, el
soroll s'hauria de classificar com a dringar (*rattle* en anglès).

{{< figure src="contacte-darrera-1.jpg" >}}

En les fotos anteriors també es pot veure l'estat de les dents. Sembla
que no hi ha un desgast significatiu. El cim de la dent està en un
estat perfecte i no es veuen rebaves que siguin conseqüència del
desgast.

## Excentricitat de l'engranatge

La següent comprovació ha estat comprovar l'excentricitat de
l'engranantge respecte el coixinet. Com es volia comprovar sobre els
flancs de les dents s'han fet servir els blocs-patró i el seu
utillatge amb uns extrems del diàmetre escaient per atacar els
flancs. Les fotografies mostren el procediment. El resultat és molt bo
i la desviació no supera pas els 0,01 mm.

{{< figure src="excentricitat-engranatge-1.jpg" >}}
{{< figure src="excentricitat-engranatge-2.jpg" >}}


## Excentricitat de la campana

També es comprova l'excentricitat de la part femella de
l'embragament. Recordeu que tenia marques d'haver estat picada amb un
martell de bola. En aquest cas, mirem de mesurar el joc amb un
comparador i es conclou que hi ha un joc que s'acosta als 0,04 mm,
segurament fruit de la deformació de la campana. Aquest és el
procediment:

{{< figure src="excentricitat-clutch.jpg" >}}

No es clar si aquesta excentricitat por influenciar el soroll. Només
ho seria si dominés la posició de l'engranatge lliscant i alterés el
contacte entre les dents. El següent test mira d'esbrinar-ho.


## Joc de l'engranatge lliscant sobre l'eix

Es aquest cas, es munta l'engranantge lliscant sobre l'eix i es mesura
el joc que té. L'objectiu és determinar (a) si hi ha massa joc i (b)
si l'embragament pot forçar l'engranatge a una posició indesitjada. Ho
comprovem amb un comparador sobre l'engranatge i forçant amb la ma un
moviment de vaibé. Ho repetim amb l'embragament connectat. El resultat
és que sense embragar el joc és aproximadament de 0,02 a 0,03 mm
---que està d'acors amb les toleràncies de Schaublin---. Embragat, el
joc se situa en els 0,01 mm, i per tant no resta forçat com podria
semblar. El joc no depen de la posició en que s'embraga.

{{< youtube id="lRqddtBRkDo" >}}

## Diàmetre del coixinet

Per tenir tota la informació, es comprova el diàmetre del coixinet en
diversos punts. El resultat va de 30,005 a 30,010 mm, que està en la
banda ajustada de la tolerància nominal. Les següents fotos ho
mostren:

{{< figure src="diam-engr-1.jpg" >}}
{{< figure src="diam-engr-2.jpg" >}}
{{< figure src="diam-engr-3.jpg" >}}

# Llegir... i mirar d'entendre

Arribat aquest punt la detecció de la causa del soroll és en un cul de
sac. La única forma d'avançar que se m'acud és llegir sobre
engranatges i, en paral·lel veure si el meu colega Jordi Bonet pot
analitzar el soroll aplicant tècniques de processat del senyal.

La cerca bibliogràfica m'ha portat a l'article de Rigaud and
Perret-Liauded titulat «Investigation of gear rattle noise including
visualization of vibro-impact regimes» al *Journal of Sound and
Vibrations*
([doi:10.1016/jsv.2019.115026](https://doi.org/10.1016/j.jsv.2019.115026)).
L'article m'ha permès entendre millor la naturalesa del soroll i,
particularment, del rattling en els engranatges.

L'article explica que la causa principal del rattling són les
fluctuacions de velocitat del sistema motriu. Les condicions que fan
que el rattling aparegui quan hi ha fluctuacions de velocitat són:

1. La inèrcia de l'engranatge conduit.
2. El fregament de l'engranatge conduit.
3. El joc entre dents.
4. La lubricació

A la fresadora SV13, les condicions (1), (2) i (4) no han canviat i
són les de disseny. El joc pot haver canviat per dues raons:

1. Hi ha desgast a les dents
2. La distància centre a centre dels engranatges ha canviat.

L'opció (2) no aplica, només (1) podria ser factible. Ambtot, com s'ha
explicat a l'apartat anterior, la inspecció de l'engranatge no detecta
desgast significatiu i els contactes semblen correctes. En aquest punt
parlo amb el servei de  [Schaublin service](https://www.schaublin.ch),
per veure si em poden facilitar els plànols de l'engranatge lliscant
per poder comprovar les distàncies entre flancs. Em diuen però, que no
me'l poden facilitar pel fet que encara està «en producció».

Només resta una causa possible: una fluctuació de la velocitat del
sistema motriu per sobre de la correcta. Aixo condueix al variador
Reeves de la màquina.

# Finalment, les corretges

Havent conclòs que la causa era en el variador de velocitat,
recomprovo les alineacions de les politges i la seva forma. No hi veig
cap defecte significatiu. Només queda jugar amb la tensió de les
corretges. Guiat per la intuició, amb passos petits vaig incementant
la tensió de les corretges sense obtenir cap resultat. A continuació,
vaig baixant la tensió de les corretges... i en un punt concret, el
soroll desapareix. Alehop!! Increïble.

El següent video mostra clarament el soroll de rattling abans de
regular la tensió. La caixa només conté els dos engranatges que fan
soroll i sense oli. En el següent vídeo, la tensió de les corretges ja
s'ha ajustat. EL rattling ha desaparegut llevat de la velocitat més
baixa on encara apareix (al final del vídeo).

{{< youtube id="a07g1CW5SYY" >}}

{{< youtube id="KByugHNjJhw" >}}

Sembla que la tensió de les corretges és doncs un factori crucial en
la suavitat del moviment que es transmet.

# Recopilació

Això ha estat una aventura enutjosa amb un final feliç. Tot comença
amb l'inesperat soroll la primera vegada que es posa en marxa la
màquina. La causa es descobreix aviat: hi ha un coixinet de bronze
molt desgastat. Sembla ben clar que canviant el coixinet el soroll
desapareixerà. El resultat, però, es decebedor. El soroll (que més
endavant es podrà qualificar com rattle) després de canviar el
coixinet continua existint. Això m'aboca a una carrera per entendre'n
la causa: mesures, muntar i desmuntar, provar, llegir,... Al final, la
causa era ben senzilla: massa tensió a les corretges. Moltes setmanes
i molta feina per una cosa ben senzilla. Una bona experiència després
de tot.



<!--
{{< image classes="fig-100 center clear" src="original.jpg" >}}

{{< youtube id="k38Vl8QqrZE" >}}
-->
