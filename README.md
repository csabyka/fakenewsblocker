# Álhír/propaganda szűrőlisták

Az eredeti változat [csgerg](https://github.com/csgerg/alternativenewsblocker) munkája, de az kb. 1 éve nem frissül(t).

A módosított változat [t1csi](https://github.com/t1csi/alternativenewsblocker) munkája. 

A lista két részre van bontva. 

1. AlternativeNewsBlocker szolgál a magyar nyelvű álhírek, illetve az idegen nyelvű, főképpen orosz propaganda-oldalak szűrésére.
A következő forrásokat használtam fel:
- [MKKP Putin Alert](https://ketfarkukutya.com/?p=505) & [MKKP Hoax Radar](http://ketfarkukutya.com/?p=9742) (magyar) 
- Urbanlegends.hu vonatkozó [gyűjtése](https://www.urbanlegends.hu/2018/01/megteveszto_atveros_magyar_oldalak_kamuhirek_lista_2018/) (magyar)
- HVG Tech rovat folyamatosan frissülő [gyűjtése](https://hvg.hu/tudomany/20150119_atveros_weboldalak) (magyar)
- [Is It Propaganda Or Not?](http://www.propornot.com/p/the-list.html) (idegen nyelvű)
- https://hup.hu/node/153781#comment-2106289

2. ANB PropagandaSTOP a teljes kormány- & kormányközeli média és azok egyéb függelékeinek, pl szatellit&kamupártok oldalainak a blokkolását célozza. Nem csak a közéleti tematikájú oldalak tartoznak ide, hanem a teljes paletta: életmódmagazinok, főzős oldalak, stb. Az ok, amiért tiltólitára került minden, egyszerűen az: bármikor megjelenhet propaganda-célú tartalom az oldalakon. Egyszerűbben: Mert, csak!

A gyűjtéshez forrásként a [444.hu](https://tldr.444.hu/2017/05/18/fideszmedia) és az [Átlátszó.hu](https://adatujsagiras.atlatszo.hu/2018/01/11/fedezze-fel-a-kormanykozeli-mediabirodalmat/) [[2]](https://atlatszo.hu/2018/03/21/itt-a-lista-olvasoink-szerint-ezek-a-kamupartok-csaltak-az-alairasaikkal/) anyagait használtam fel.

A listák forrásául szolgáló anyagok/oldalak fel vannak tüntetve a lista kikommentelt részeiben is. 

## Feliratkozás asztali gépen:
A feliratkozáshoz a következő böngésző-kiegészítők valamelyikét szükséges telepíteni:
[uBlock Origin](https://github.com/gorhill/uBlock) | [Nano Adblocker](https://github.com/NanoAdblocker/NanoCore#nano-adblocker-core) | [Adblock Plus](https://adblockplus.org/)

Az alábbi hivatkozásokra kattintás után a "Proceed to this site." linkre kell kattintani, újfent.
- [ANB aka AlternativeNewsBlocker](https://preview.tinyurl.com/t1csiAltNewsBlk)
- [ANB PropagandaSTOP](https://preview.tinyurl.com/t1csiPropSTOP) 

Lehetőség van host alapú tiltásra is: [ANB host file](https://raw.githubusercontent.com/t1csi/alternativenewsblocker/master/hosts.txt)

Windows tulajdonosoknak javaslom a köv. oldalakat tájékozódni ebben a témában: [Blocking Unwanted Connections with a Hosts File](http://winhelp2002.mvps.org/hosts.htm) | [SevenBlack/HOSTS](https://github.com/StevenBlack/hosts) | [WinSpyBlocker](https://github.com/winspyblocker)

## Feliratkozás android rendszerű mobiltelefonon:
Érdemes [F-droid](https://f-droid.org) tárolót használni. A használathoz fel kell rakni, root-olt telefon esetén az [Adaway-t](https://f-droid.org/en/packages/org.adaway/), root nélküli készüléknél a következők bármelyikét ízléstől és egyéni preferenciától függően: [DNS66](https://f-droid.org/en/packages/org.jak_linux.dns66/) | [Blokada](https://f-droid.org/en/packages/org.blokada.alarm/) | [Netguard](https://f-droid.org/en/packages/eu.faircode.netguard/) | [AdGuard](https://f-droid.org/en/packages/com.adguard.android.contentblocker/)

Az egyéni lista hozzáadásakor be kell másolni az alábbi hivatkozást:
[ANB host file](https://raw.githubusercontent.com/t1csi/alternativenewsblocker/master/hosts.txt)

Ezen kívül Androidon a [Fennec Browser](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/) támogatja az asztali rendszereken megszokott böngésző-alapú szűrést.
____________________________________________________________________
#### Tennivalók, tervek, 5letek
* kamupártok FB oldalainak felvétele/felderítése
* álhíroldalak FB jelenlétének feltérképezése
* oldalak elérhetőségének (fél)automatikus ellenőrzése:
  * Script az olyan oldalak kigyomláláshoz amelyek eleve nem is elérhetőek - egysorosakkal megoldható
  * [Script](https://raw.githubusercontent.com/t1csi/alternativenewsblocker/master/capture-screenshots.sh) (w/ [webkit2png](http://www.paulhammond.org/webkit2png/)) az elérhető oldalak 'viszonylag' gyors, manuális ellenőrzéséhez - **kész**
