<img align="left" src="https://i.imgur.com/M5T1BL9.png">
<br/><br/>

Neatkarīgs decentralizēts ISP mūsu draugiem

## Es esmu lietotājs
Lai izveidotu savienojumu ar jau esošo Medium mezglu, jums ir jāizvēlas [jūsu pilsēta](https://github.com/medium-isp/medium/tree/master/ru) un atrodiet tuvāko operatoru.

Lai izveidotu savienojumu, jums jāizveido jauns savienojums ar šādiem parametriem: SSID - «Medium» (bez pēdiņām), autentifikācijas veids - bez paroles.

Esiet uzmanīgi: vidējais tīkls pēc noklusējuma ir paslēpts no nevēlamām acīm; pieejamo tīklu sarakstā tas netiks rādīts, kamēr nav izveidots jauns savienojums ar iepriekš minētajiem parametriem.

Lai pārbaudītu tīklu, mēģiniet apmeklēt portālu [medium.i2p](http://medium.i2p) pēc pievienošanas.

## Es esmu operators
Lai palielinātu vidējā tīkla mezglu, jums ir nepieciešamas šādas lietas:
* Interneta pieslēgums
* Bezmaksas maršrutētājs
* Brīvais laiks un entuziasms

### 1. solis. Savienojuma izveide ar I2P tīklu
Pirmkārt, jums ir nepieciešams izveidot savienojumu ar I2P tīklu. To var izdarīt ar [i2pd](https://github.com/PurpleI2P/i2pd/wiki/Using-i2pd).

### 2. solis. Savienojuma koplietošana
Kad savienojums ir izveidots, jums ir jākonfigurē bezvadu maršrutētājs, lai visa satiksme iet caur starpniekserveri, kas atrodas serverī, kurā tika paaugstināts i2pd pakalpojums. Tiek pieņemts, ka tas ir izvietots vietējā mājas tīklā. Piemēram, 192.168.0.1:4444.

Pievērsiet īpašu uzmanību tam, ka autentiskumam tīklam ir jābūt šādiem parametriem: SSID - Vidējs, bez paroles, tīkls ir slēpts.

### 3. solis. Bloķēt satiksmi
Atkarībā no jūsu maršrutētāja modeļa liegt jebkādu satiksmi, kas kaut kādā veidā ir saistīta ar ārējo internetu.

### 4. solis. Punkta pievienošana publiskajam sarakstam
Pēc piekļuves punkta konfigurācijas pabeigšanas un tās darbības pārbaudes varat to pievienot [publiskais saraksts](https://github.com/medium-isp/medium/blob/master/CONTRIBUTING.md).
