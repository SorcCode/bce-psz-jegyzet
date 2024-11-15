2.3., 2.4., 5. és 6.4. fejezetek
![[2ea_VP.pdf]]

**Örökjáradék** (perpetuities): olyan pénzügyi koncepció, amelyben elméletileg örökre egyenletes szintű pénzáramlás érkezik
$$P = \frac{C}{r}$$\*Minden pénzáramlás az időszal végén érkezik, r vízszintes 

Egyenletes ütemben növekvő örökjáradék (pl albérlet bérleti díja a tulajdonosnak)
$$
P=\frac{C}{r-g}
$$
Ahol g az éves növekedés üteme

**Annuitás**: olyan eszköz, amely meghatározott számú éven keresztül minden évben fix összeget fizet
$$
PV_{\text{Annuitas faktor}} = C * \left[ \frac{1}{r} * \left( 1- \frac{1}{(1+r)^t} \right) \right]
$$
$$
PV = C * AF
$$
AF: Annuitás faktor

## 5. fejezet

Mi alapján válasszunk jó projektet?
3 legfőbb szabály: 
	Pozitív NPV
	MINDEN jövőbeli pénzáramlást figyelembe kell venni
	Egy dollár ma többet ér, mint egy dollár holnap
	A nettó jelenérték kizárólag az **előre jelzett pénzáramlástól** és a **tőke alternatív költségétől** függ (nem tudunk ilyen adatokat szerezni)

#### Az NPV sokszor nem egyértelmű
Mi történik, ha beruházás közben választási lehetőség van?
Mi történik, ha megváltozik a cash flow?

**Az IRR a legnépszerűbb mutató**

#### Egyszerű megtérülési idő (Payback period)
Azoknak az éveknek a száma, amely alatt a beruházásból származó pénzáramlások NOMINÁLISAN elérik a kezdeti beruházási összeget

Probléma:
	Figyelmen kívül hagyja a későbbi évek pénzforgalmát
	Figyelmen kívül hagyja a jövőbeli cash flow jelenértékét
	Ez alapján sorrend a megállapításánál, kölcsönösen kizáró befektetések is problémát okozhat
	Használat: elég népszerű a gyors értékelésekhez

#### Diszkontált megtérülési idő
Azoknak az éveknek a száma, amely alatt a beruházásból származó pénzáramlások JELENÉRTÉKBEN elérik a kezdeti beruházási összeget

#### Könyv szerinti megtérülési ráta
Átlagos bevétel osztva az átlagos könyv szerinti értékkel a projekt élettartama alatt
Más néven számviteli megtérülési ráta

#### Belső megtérülési ráta
Mi az a diszkontráta, amely mellett a nettó jelenérték nulla

Buktatói:
	Bizonyos pénzáramlások két különböző diszkontráta mellett is NPV = 0-át eredményezhetnek
	Lehet olyan, hogy az IRR értéke nulla, az NPV értéke pedig pozitív
	Kölcsönösen kizáró projektek (lehet, hogy egy 10000-es projektre van pénzem, de egy 20000-esre nincsen)


### Az lényeg az, hogy ábrázold

#### Profitabilitási index
$$
\text{Profitability index} = \frac{\text{NPV}}{\text{kezdeti befektetett tőke}}
$$
Tőke szűkösség: korlátos a befektetésre rendelkezésre álló pénzeszközök mennyisége
Puha szűkösség: korlátos a menedzsment kapacitások korlátozottsága miatt: a vállalat belső politikáján alapuló korlátozások. a vállalat megkövetelhet egy előre meghatározott minimális megtérülési mutatót

## 6.4 fejezet
Választás különböző élettartamú projektek között
Egyenértékes (Equivalent Annual Cash Flow): az a periódusonkénti pénzáramlás, amelynek jelenértéke megegyezik a projekt tényleges pénzáramlásával


# Gyakorlat
Hogyan értékelünk egy beruházást?
Felírjuk a Cash Flow-t és meghatározzuk az NPV-t
$$
\text{NPV} = \sum_{t=0}^{n}\frac{\text{CF}_{t}}{(1+r)^t}
$$

Kapcsolódó linkek:
[[Fogalomtár - VP]]
[[Általános - VP]]
#vpu
#bce