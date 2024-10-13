---
title: "Schaublin 13: refent l'armari elèctric"
slug: sv13elect
date: 2024-05-26
coverImage: "placa-entrada.jpg"
tags:
- tech.electricitat
- schaublin-13
categories:
- restauració de màquines
- schaublin 13
keywords:
- Schaublin 13
- Instal·lació elèctrica
draft: false
---

L'últim pas en la reconstrucció de la Schaublin 13 s'ha centrat en el
quadre elèctric i el cablejat. La màquina ha estat adaptada a la xarxa
ordinària monofàsica de 230V utilitzant variadors de freqüència (VFD),
i tots els circuits de control s'ha refet per tal que fóssin assumits
pels mateixos VFD.

<!--more-->

Igual que amb altres màquines reconstruïdes, he adaptat la Schaublin 13
per funcionar amb corrent domèstic estàndard monofàsic de 230V. La
clau per al nou cablejat és l'ús de VFDs, que permeten que els motors
trifàsics de la màquina funcionin amb alimentació monofàsica. Els VFDs
moderns també inclouen moltes funcions lògiques, cosa que facilita
substituir els antics circuits de relés per la lògica integrada dels
VFD. Sempre intento mantenir la interfície de control igual que la
màquina original, de manera que, des de la perspectiva de l'usuari, no
hi hagi cap diferència. Això implica utilitzar els interruptors
originals d'una manera específica, però normalment és factible. Amb la
Schaublin 13, ha estat senzill d'aconseguir-ho.

# Passos de la reconstrucció #
	
Durant la reconstrucció de la màquina, vaig substituir les canonades i
mànegues de protecció del cablejat intern per noves. A part d'això i de
pintar el quadre, vaig seguir aquests passos:

1. **Desmuntatge, neteja i engreixat (si calia) de tots els interruptors
   originals.** Els interruptors originals eren de gran qualitat, i la
   majoria estaven en bon estat. L'interruptor principal necessitava
   alguns ajustos per reparar peces de plàstic trencades.
2. **Creació d'un pla detallat de cablejat per a l'interruptor rotatiu.**
   Això em va ajudar a entendre com utilitzar-lo per gestionar la lògica
   del VFD.
3. **Extracció de la placa de suport i desmuntatge de tots els relés,
   contactors i dispositius de protecció que s'anaven a descartar.** Això
   va alliberar prou espai a la placa per instal·lar els nous VFDs i
   altres components necessaris.
4. **Fixació mecànica dels VFDs i altres components.** En alguns casos,
   va ser necessari utilitzar rails DIN per als dispositius elèctrics. La
   majoria dels dispositius es van fixar amb cargols hexagonals de cap
   reduït i els originals. En alguns casos, es van necessitar cargols de
   cap ultra-baix. Aquests no són fàcils de trobar, però
   [ARSAM](https://shop.arsam.es) els ven.
5. **Recablejat de tots els dispositius segons el nou disseny.**
   Testat incrementalment que el cablejat funcionava segons les
   expectatives.
6. **Instal·lació de la placa al quadre.**
7. **Connexió de les parts de la màquina (motors, interruptors, etc.)
   als borns de connexió de la placa.**
8. **Configuració i programació dels nous VFDs segons les funcions
   requerides.**

{{< figure src="placa-1.jpg" 
	title="La placa de control elèctric gairebé recablejada." >}}


# Algunes notes #

1. **VFDs escollits:** Vaig optar pels compactes VFD de Schneider perquè
   la seva mida s'ajusta bé al quadre. El gran per al motor principal és el
   [Altivar
   320U15M2C](https://www.se.com/us/en/product-range/63440-altivar-320-variable-frequency-drive-vfd).
   Els altres dos, per al motor d'avanç ràpid i la bomba de refrigerant,
   són els models 320U06M2C i 320U02M2C.
2. **Refrigeració:** Hi ha prou espai a la part superior dels VFDs per
   garantir una refrigeració adequada. Es pressuposa que la refrigeració es
   gestionarà a través de la transmissió del quadre sense cap dispositiu
   especial de refrigeració. Si això resulta insuficient, instal·laré un
   dispositiu de refrigeració al quadre.
3. **Circuit de control:** Com que es controlen tres VFDs amb un sol
   circuit, Schneider recomana afegir una font d'alimentació independent
   per al circuit de control.

{{< figure src="armari-1.jpg" 
	loading="lazy"
	title="Acabant les connexions amb l'armari muntat a la fresadora." >}}
	
# Esquema de cablejat #

També adjunto l'[esquema complet del recablejat de la Schaublin
13](sv13-rewiring.pdf), incloent els principals paràmetres utilitzats per
configurar els VFDs. És un conjunt de fulls pdf que també inclou les
referències dels dispositius utilitzats.

