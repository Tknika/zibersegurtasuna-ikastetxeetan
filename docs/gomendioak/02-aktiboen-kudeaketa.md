---
sidebar_position: 2
tags:
  - identifikatu
---

# 2-Aktiboen kudeaketa

Ikastetxeko aktiboak identifikatzea, antolatzea eta kudeatzea ezinbestekoa da.

## Zergaitik da garrantzitsua?

- Identifikazio eta antolaketa zehatzak ikastetxeak dituen aktibo guztien ikuspegi bat eskeiniko digu bere osotasunean. Era berean, segurtasun maila ezberdinak ezarri ahal izango ditugu, aktibo bakoitzaren garrantziaren arabera.
- Identifikazio egokiak eguneraketen kudeaketa egokia egiten eta ahultasunak garaiz konpontzen lagunduko digute.
- Eguneroko operatiba modu eraginkorrean egitea erreztuko digu.

## Zein motako atazak hartzen ditu barne?

- **Antolaketa** mailakoak
- Soluzio **teknikoen** ezarpena

## Gomendio zerrenda

1. Aktiboen **inbentarioa** egunean eramatea komeni da eta **ahalik eta osatuena**. Modu efizientean kudeatua (automatizatua), datuak analizatzeko aukerak eskeintzen dituenak.
	- Hardware inbentarioa
	- Software inbentarioa
	- Sareko topologia diagrama ondo dokumentatuta
	- Zerbitzuen inbentarioa
	- Erabiltzaileen inbentarioa
2. Aktiboetan **lehentasuna ezarri**: aktibo mota, kritizitate, baliabide eta inpaktuak kontutan hartuta
3. Aktibo hauei **betebehar minimo batzuk** ezarri eta hauen betetzea ziurtatu
4. Aktiboetan dauden **ahultasunak bilatu** eta dokumentatu (arrisku kudeaketa)
5. Kontrol neurriak ezarri ezagutzen ez ditugun aktiboak ez izateko (software instalazioak, bestelako gailuak). Noizean behin kontrol neurri hauek saihesten saiatu.
6. Aktiboetan gerta daitezkeen **arazoak aurreikusi**, adibidez:
	- Zerbitzariaren diskoaren okupazioa monitorizatu eta aurrez definitutako maila batera heltzen denean, alertak bidali
	- Zerbitzuen eskuragarritasuna monitorizatu (wifi antenak, web zerbitzuak, ....), eta arazoak hasieratik identifikatu, arazo larriak bihurtu aurretik

## Baliabideak

### Tresnak
- [GLPI](https://glpi-project.org/): Hardware/Software inbentario automatizatuak egiteko tresna librea (soft. librea).
- [LibreNMS](https://www.librenms.org/): sareko gailuak inbentariatzeko eta monitorizatzeko tresna (soft. librea).
- [Observium](https://www.observium.org/): sareko gailuak inbentariatzeko eta monitorizatzeko tresna (soft. librea).
- [NetBox](https://netbox.dev/): sareko konfigurazioa (IP tartea, konexioak, etab) inbentariatzeko tresna (soft. librea).
- [Microsoft Intune](https://www.microsoft.com/es-es/security/business/microsoft-intune): gailu guztien inbentario eta kudeaketa aurreratua egiteko tresna (ordainezkoa).