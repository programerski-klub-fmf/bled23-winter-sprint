---
title: Zimski sprint
description: Na tem srečanju se bomo posvetili delu na projektih programerske narave.
layout: page
---

Delavnica je namenjena analizi trenutnega stanja in potreb po IKT storitvah za pedagoškemu procesu.

Teme delavnice:

* IKT podpora učnim procesom,
* algoritmično generiranje nalog na področjih matematike in računalništva,
* analiza podobnosti nalog in rešitev iz programiranja, vključno z analizo najpogostejših vzorcev.

## Program

* **Petek:** prihod in registracija, sestanek za načrtovanje dela v skupinah.
* **Sobota:** delo v skupinah.
* **Nedelja:** delo v skupinah, predstavitve skupin s poročili o opravljenem delu in evalvacija, odhod.

## Predlogi delovnih skupin

### Projekt Tomo: infrastruktura baze nalog

Storitev [Projekt Tomo](https://www.projekt-tomo.si) je bila prvotno namenjena podpori pri poučevanju programerskih predmetov na Fakulteti za matematiko in fiziko, v zadnjem času pa postaja vedno bolj razširjena po srednjih in osnovnih šolah. S tem so jo pri svojih predmetih začeli uporabljati tudi učitelji, ki znajo dobro posredovati osnove programiranja, vendar programiranje ni njihovo matično področje. Ti učitelji ne želijo izkoristiti vseh zmožnosti, ki jih ponuja storitev, temveč bi raje uporabili vnaprej pripravljene sklope nalog. Nekaj takih sklopov je vsebinsko že pripravljenih v okviru drugih projektov, vendar storitev takemu deljenju nudi le osnovno podporo. Učitelji lahko pripravljene sklope prekopirajo v svoj predmet, vendar na tisti točki izgubijo možnosti nadaljnjih posodobitev. Ugotoviti bi bilo treba, kako prilagoditi strukturo baze nalog, da bo omogočala tako podvajanje kot "izposojo" nalog.

### Projekt Tomo: analiza podobnosti nalog in rešitev

Kot omenjeno zgoraj, so učitelji pripravljene sklope nalog, ki so jih želeli uporabiti v svojih predmetih, trenutno lahko le podvojili. Na ta način je nastalo precej kopij enih in istih nalog v več različicah, odvisno od trenutka podvojitve. Učiteljem, ki so naloge poprej podvojili bi lahko ponudili, da uporabijo vsebino iz aktualnih različic nalog. Ker gre v bazi sedaj za neodvisne naloge, bi bilo potrebno analizirati zgodovino sprememb in iz nje ugotoviti prvoten izvor nalog ter učiteljem ponuditi enostavno možnost posodobitve.

Na podoben način bi lahko analizirali sorodonost oddanih rešitev, saj veliko učiteljev želi preveriti, ali učenci naloge oddajajo samostojno. Tudi pri oddanih rešitvah imamo dostop do zgodovine oddaj, na osnovi katere bi lahko razvili hevristike za ugotavljanje morebitnih prepisovanj.

### Nadlogar: prenos generatorjev nalog na spletno storitev

Storitev [Nadlogar](https://www.nadlogar.si) učiteljem omogoča enostavno generiranje tipskih matematičnih nalog. Je nadgraditev [knjižnice za generiranje nalog v Pythonu](https://github.com/ursa16180/generiranje-nalog/tree/python) z preprostejšim uporabniškim vmesnikom. Ob prehodu na spletno storitev bo potrebno vse obstoječe naloge ustrezno prenesti v nov format, pri čemer je posebej zahteven problem prenos grafičnih nalog.
