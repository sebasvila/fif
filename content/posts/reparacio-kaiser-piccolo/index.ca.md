---
title: "Reparació del capçal de mandrinar Kaiser Piccolo"
slug: kaiser-piccolo-repair
date: 2024-10-14
coverImage: "head-4.jpg"
tags:
- tech.tornejat
- tech.fresat
- leinen-lz4sb
- schaublin-13
- wörner-b13
- projectes
- eines
categories:
- projectes
keywords:
- kaiser piccolo
- capçal mandrinar
- refrentat automàtic
- diacator
draft: false
---

El Kaiser Piccolo és un capçal de mandrinar mitjà exquisidament
fabricat amb funcions de mandrinat i refrentat automàtic. Tinc un
capçal amb un con ISO30 en molt bon estat, juntament amb un bon
conjunt d'eines. En provar-lo, va funcionar molt bé, però no podia
canviar fàcilment entre les funcions de refrentat i mandrinat
(marcades com P i A al capçal, potser pel francès «planage» i
«alésage»). Cal revisar-lo per solucionar aquest bloqueig.

<!--more-->

{{< toc >}}

## El capçal de mandrinar Kaiser Piccolo

El capçal de mandrinar Kaiser és un capçal de mida mitjana amb un rang
de mandrinat i planejat de 2mm a 180mm. El desplaçament del carro
és d'aproximadament 30mm com a màxim. Té tres funcions:

- mandrinat, ajustable en fraccions de 0,005mm
- refrentat, el carro té un avanç automàtic de 0,05mm per revolució
- retorn ràpid del carro, torna automàticament a 2,5mm per revolució
  
El capçal té un embragatge de fricció que afita l'esforç del carro i
permet que el seu desplaçament es limiti amb topalls.

Hi ha dues versions del capçal. L'antiga es pot reconèixer fàcilment
pel seu petit commutador rotatiu per seleccionar les funcions de
mandrinat i refrentat. El meu és una versió nova amb una tija
STP. Aquesta és una tija específica de Kaiser utilitzada com a
interfície amb altres tiges estàndard. En aquest cas, munta una tija
ISO30.

{{< figure src="head-1.jpg" loading="lazy" title="Una imatge del capçal de mandrinar Kaiser Piccolo" >}}

{{< figure src="head-3.jpg" loading="lazy" title="Detall del capçal de mandrinar Kaiser Piccolo" >}}


## El commutador P-A del capçal està bloquejat 

El commutador del meu capçal sembla bloquejat en la posició A. És
sorprenent, perquè el capçal sembla haver estat ben utilitzat i no
presenta signes d'abús. No obstant això, després de dies lluitant amb
el commutador, el resultat és clar: està bloquejat.

El capçal s'ha de revisar per solucionar aquest bloqueig.

## Com desmuntar el Kaiser Piccolo?

El primer repte és desmuntar el capçal. Després d'una cerca en alguns
fòrums i una conversa fructífera amb Charles, el misteri es va
resoldre: el capçal s'ha de desmuntar afluixant una femella plana
especial situada a la part superior del capçal.

Primer, cal enretirar la tija ISO30 del con STP. Això és fàcil de fer
ajustant la tija ISO30 en el cargol de banc i descollant tot el
capçal. És útil escalfar lleugerament la tija ISO30. Usa una clau
anglesa de bona mida i ajusta-la al carro. Descolla en sentit
antihorari. Està fort, però una clau prou gran farà la feina.

Sota l'adaptador ISO30 apareixerà una femella plana amb tres petits
forats. Aquesta és la femella que allibera totes les parts interiors
del capçal. Els forats estan plens amb un passador que reté la femella
a la part inferior. Aquests passadors s'han de foradar completament i
retirar. Necessitaràs una broca extrallarga o una extensió casolana.

{{< figure src="forat-fiador-1.jpg" link="forat-fiador-1.jpg" loading="lazy" title="Foradat dels passadors de la femella del capçal" >}}

El diàmetre del forat és d'1,5mm i s'ha de foradar uns 6 mm de
profunditat. De vegades, una broca de diàmetre més petit, d'uns
1,25mm, també pot ser útil. L'objectiu és eliminar completament els
passadors. Notaràs quan el trepant impacta amb la part dura al
fons. Sigues suau i procura no marcar la part inferior amb la broca.

{{< figure src="forat-fiador-2.jpg" loading="lazy" title="Detall del procés de foradat d'un passador" >}}

{{< figure src="forat-allargador.jpg" loading="lazy" title="Treballant una extensió per a la broca a la fresadora" >}}


## Fabricar la clau especial per als passadors

Un cop retirats els passadors, caldrà una clau especial per a
descollar la femella. En vaig fer una a partir d'un anell d'alumini i
alguns trossos d'acer blau de rellotger (tamponstahl).

El primer pas és mesurar la posició exacta dels forats. Si assumeixes
que estan en el mateix cercle i que tots es troben a un angle de 120
graus, només cal mesurar la distància entre els forats. Fent servir un
parell de broques com a passadors de referència, es pot mesurar la
distància amb un peu de rei o un micròmetre. Després, una mica de
trigonometria farà la resta.

{{< figure src="mesura-cc.jpg" loading="lazy" title="Mesura de la distància entre forats amb broques" >}}
	
{{< figure src="calcul.jpg" loading="lazy" title="Càlcul de les distàncies principals de la clau especial" >}}

El resultat és que els centres dels forats dels passadors es troben en
un cercle de 30mm centrat en l'eix del capçal. Amb això al cap, vaig
tornejar un anell gruixut d'alumini. En aquest, es van foradar tres
forats d'1,5mm sobre el diàmetre 30mm fent servir un divisor a la
fresadora Schaublin 13.

{{< figure src="centrant-clau-2.jpg" loading="lazy" title="Alineació del centre de la peça amb el calibrador Diacator" >}}

{{< figure src="centrant-clau-1.jpg" loading="lazy" title="Detall del procés d'alineació" >}}

{{< figure src="puntejant.jpg" loading="lazy" title="Puntejat dels punts de foradat de la clau" >}}
	
{{< figure src="foradant.jpg" loading="lazy" title="Foradat dels forats per als passadors de la clau" >}}
	
Un cop trepat l'anell, talla alguns passadors llargs d'acer blau de
rellotger de 1,5 mm. Aquest tipus de barres petites d'acer utilitzades
pels rellotgers són de bona qualitat, fàcils de trobar en lots petits
i endurides a un nivell interessant: són dures però es poden treballar
prou bé. Els passadors han de sobresortir uns 4 mm de l'anell. Es
poden fixar a l'anell amb una mica de cola de cianoacrilat.

{{< figure src="clau-1.jpg" loading="lazy" title="La clau especial per al Kaiser Piccolo (costat de la femella)" >}}

Si la clau s'adapta a la femella, forada a l'altre costat uns forats
de 4mm per girar-la amb una clau de pius estàndard. La següent imatge
ho mostra. Recorda que la clau de pius no ha de fregar amb el con STP
del capçal.

{{< figure src="clau-2.jpg" loading="lazy" title="La clau especial per al Kaiser Piccolo (costat superior)" >}}



## Desmuntar el capçal de mandrinar

Ara ja es pot desmuntar el capçal Kaiser Piccolo. És útil marcar la
posició original de la femella per ajustar-la correctament quan es
torni a muntar. Després, només cal subjectar-la al cargol de banc i
descollar lleugerament la femella superior fins que es pugui girar
amb la mà.

{{< alert warning >}} 
No descollis completament la femella! A
l'interior del capçal hi ha un parell de coixinets de boles que cauran
si ho fas.
{{< /alert >}}

És molt pràctic treballar en el capçal mantenint-lo dins d'un
contenidor de plàstic per evitar perdre les boles. Amb aquesta cura,
només cal descollar la femella, els anells del capçal quedaran
alliberats i apareixerà el coixinet superior. Guarda les boles d'acer
en un pot segur fent servir unes pinces. Hi ha 54 boles de 2 mm.

{{< figure src="femella-superior.jpg" loading="lazy" title="La femella descollada i el coixinet superior" >}}

Un cop l'anell superior s'ha enretirat, apareixerà la part superior
del segon anell. Aquest és l'anell que es pot subjectar amb un
bastonet mentre es treballa. Apareixeran dues boles diferents. Totes
dues mesuren 2,5mm i són una mica més grans que les boles del
coixinet. La primera és una bola lliscant situada a sobre de l'eix de
l'embragatge (marcada com A a la següent figura). La segona és una
bola i una molla que retenen l'anell superior en una posició
específica (marcada com B).

{{< figure src="rodament-superior.jpg" loading="lazy" title="Part superior del segon anell" 
	caption=`Marcat com (A) hi ha l'eix de l'embragatge. Marcat com (B) hi ha la molla de retenció de l'anell superior.` >}}

El segon anell es pot treure fàcilment. Només cal estirar-lo a través
de la tija. Descobriràs els engranatges interns que mouen el carro en
mode automàtic. A la part inferior d'aquest anell hi ha el coixinet
inferior de boles, vés amb compte. Aquest coixinet té 90 boles de 2
mm.

{{< figure src="anell-pinyons.jpg" loading="lazy" title="Part inferior del segon anell" >}}

{{< figure src="rodament-inferior.jpg" loading="lazy" 
	title="El capçal després de treure el segon anell" 
	caption=`A l'esquerra, hi ha el segon anell. A la dreta pots veure el coixinet inferior i els dos
	engranatges centrals. L'engranatge superior està unit a l'eix
	mitjançant una petita claveta. Fixat' en el petit forat utilitzat per
    bloquejar la femella superior introduint els passadors. L'engranatge
	inferior, tot just visible sota l'engranatge superior, està unit al
	tercer anell i gira lliurement.` >}}

Si treus amb cura el tercer anell, descobriràs l'engranatge intern que
fa girar l'engranatge principal del capçal. L'engranatge principal del
capçal desplaça el carro. Mira les imatges a continuació.

{{< figure src="anell-inferior.jpg" loading="lazy" 
	title="El tercer anell" 
	caption=`A l'interior pots apreciar l'engranatge intern que engrana amb l'engranatge principal. 
	L'engranatge principal es veu lleugerament a la part superior dreta.`>}}

{{< figure src="conjunt.jpg" loading="lazy" title="El Kaiser Piccolo completament desmuntat" >}}

{{< figure src="engranatge-carro.jpg" loading="lazy" title="Detall de l'engranatge principal" caption=`Aquest engranatge és mogut pel tercer anell i mou el carro del capçal.` >}}
	
{{< figure src="guia-portaeines.jpg" loading="lazy" title="L'engranatge principal on engrana el carro del capçal" >}}

{{< figure src="portaeines.jpg" loading="lazy" 
	title="La cara oculta del carro on engrana l'engranatge principal" 
	caption=`Fixa't que l'engranatge principal està compost per engranatges de 
	diàmetres diferents en el mateix conjunt. Només els petits engranatges laterals
	mouen el carro. L'engranatge principal és mogut pel tercer anell.` >}}


## Solució del bloqueig del Kaiser Piccolo

Finalment, és hora de solucionar el bloqueig del capçal
de mandrinar. Després de desmuntar completament el capçal, no vaig veure
cap problema que pogués explicar el bloqueig. El vaig muntar de nou i
el capçal es va tornar a bloquejar. Vaig repetir el procés de muntatge
i desmuntatge diverses vegades amb el mateix resultat. Al final, vaig
deduir que l'efecte de bloqueig havia de ser causat pel mecanisme de
retenció. La bola del retenidor té un diàmetre de 2,5mm mentre que el
forat de la molla mesura 3,1mm. Em sembla que la bola es desplaça cap
a un costat del forat quan es gira l'anell superior i queda atrapada
d'alguna manera. Això és estrany, ja que la bola sembla ser
l'original. Vaig provar amb una bola de 3mm i tot va funcionar com la
seda!

Queda la pregunta sobre quin és el diàmetre correcte per a la bola del
retenidor i, si els 2,5mm són incorrectes, per què hi ha una bola de
2,5mm? En qualsevol cas, ara funciona com s'esperava.

Tots els anells i coixinets es van muntar de nou i la femella es va
ajustar fins a la marca que havíem fet abans de desmuntar-lo. A
continuació, s'introdueix un únic passador en l'únic forat de
bloqueig. El passador està fet de llautó per facilitar-ne el trepat de
nou si cal.

## Com funciona el capçal

{{< figure src="gearing.jpg" loading="lazy" title="Esbós dels mecanismes interns del Kaiser Piccolo" >}}

L'engranatge principal és un engranatge escalonat. Els engranatges
exteriors engranen amb la cremallera del carro del capçal. Quan
l'engranatge principal gira, mou el carro. La part central de
l'engranatge principal engrana amb l'engranatge intern del tercer
anell. Tots dos formen un sistema d'engranatges creuats, on un dels
engranatges és intern. Així, quan gires el tercer anell, l'engranatge
intern força l'engranatge principal a girar i el carro a moure's.

Els dos petits pinyons són sobre el mateix eix però hi ha un mecanisme
d'embragatge que permet que girin independentment o
conjuntament. Aquest embragatge és activat per l'anell superior (no
mostrat al dibuix). Quan l'anell superior està en posició A
(mandrinar), els pinyons són independents entre si. No obstant això,
quan l'anell superior està en posició P (refrentat automàtic), els
pinyons estan units.

L'engranatge de 52 dents està unit solidàriament a l'eix del capçal de
mandrinar. Així, en la posició P, i amb el segon anell fix en una
posició, quan l'eix gira, també ho fa el conjunt de pinyons. Com que
l'engranatge del tercer anell té 50 dents, hi ha una acció
diferencial, i cada gir de l'eix del capçal fa que l'engranatge de 50
dents no giri completament, sinó una mica menys: exactament 1/50 de
revolució menys. Això significa que el tercer anell s'ha desplaçat
1/50 de revolució. Per tant, el carro s'ha desplaçat la distància
proporcional.

Aquest gran efecte de reducció permet a un usuari fixar el segon anell
amb el bastonet de retenció aplicant una lleugera pressió. Al mateix
temps, per evitar fer malbé el capçal, un embragatge de fricció
connecta l'engranatge de 50 dents amb l'engranatge intern del tercer
anell. En lloc de forçar massa el mecanisme, si el carro es bloqueja,
l'embragatge de fricció llisca. Aquest és també l'efecte que provoquen
els topalls del carro.

## Referències interessants

Algunes referències que poden ser útils:

- Alguns PM amb Charles (Demoniakteam a PassionUsinages), que
  em van ajudar a entendre com desmuntar el
  capçal. https://passion-usinages.forumgratuit.org/t1399-tete-a-aleser-kaiser
- Aquesta publicació d'Arnljot Seem
   https://www.instagram.com/p/B0V0FuWIZZy
- Aquest fil a Metalworkforums
  https://metalworkforums.com/f65/t180755-disecting-imperial-majesty
- https://passion-usinages.forumgratuit.org/t9973-tete-a-aleser-kaiser-piccolo
