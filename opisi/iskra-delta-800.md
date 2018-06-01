---
layout: page
title: "ID 800"
---

# Iskra Delta 800

<img style="float: right; height: 30%;" src="{{site.url}}/assets/img/ID800/id800_1.jpg">

<br>

 - 1970-1990
 - 4.5Mhz Procesor J11
 - Do 4MB RAM pomnilnika
 - 4KB ROM pomnilnik
 - Operacijski sistem Delta/M
 - RS232

<br>
<br>	

------

<br>

Iskra Delta 800 je paralelni binarni 16-bitni računalniški sistem splošne namembnosti. Razvit je bil na osnovi takrat popularnega miniračunalnika PDP-11, proizvajanega med leti 1970 do 1990 s strani ameriškega podjetja DEC (Digital Equipment Corporation). 

Uporabljal je procesor J11, katerega povprečni čas ukaznega cikla je bil 225ns. Vseboval je 8 16-bitnih registrov, ki so vključevali programski števec in kazalec na sklad, na katerem se je zapisala vsebina registrov od preklopu med opravili. Procesor je razlikoval 8 prioritetnih nivojev izvajanja programov in opravila izvajal v uporabniškem ali privilegiranem načinu. V privilegiranem načinu so se lahko izvajali vsi ukazi, ta način so uporabljali monitorji in super nadzorni programi. V uporabniškem načinu so bile onemogočene menjave programov iz privilegiranega načina in ustavljanje procesorja, omejena pa je bila tudi rezervacija pomnilnika.

Za preklapljanje med opravili so bile omogočene gnezdene prekinitve v štirih prioritetnih nivojih. Naprava je podala zahtevo za prekinitev preko ene izmed štirih linij na vodilu, ki so določale vsaka svojo prioriteto. V primeru, da je prioriteta prekinitvene zahteve bila višja od prioritete trenutno izvajanega opravila, je procesor na vodilo postavil naslov vektorja, ki je kazal na primeren prekinitveno strežni program. 

Procesor je bil, tako kot ostale komponente računalnika, povezan na "Delta vodilo", ki je bila Deltina različica vodila "Unibus". Gre za dvosmerno asinhrono vodilo z ločenimi naslovnimi, podatkovnimi ter kontrolnimi linijami. Hitrosti vodila so segale do 1.9M bit/s. Na vodilo je bilo možno dodati do 20 naprav, z uporabo REPEATER-ja pa tudi več. 

Z ločenim pomnilniškim vodilom je bil procesor povezan z glavnim pomnilnikom. V osnovi je procesor pomnilnik naslavljal s 16-bitnimi naslovi, ki pa so se lahko razširili na 18 ali 22-bitne in tako naslovili do 4MB pomnilnika. Najvišji 4k naslovnega prostora so bili rezervirani za naslavljanje vhodno izhodnih naprav

Za hitrejši ponovni dostop do pogosto izvajanih ukazov, so se deli glavnega pomnilnika prepisovali v hitrejši ROM medpomnilnik velikosti 2KB (nekje piše naj bi imel 4KB)

Izkoriščanje uporabljenih komponent je omogčal operacijski sistem DELTA/M, povezava z zunanjimi komponentami pa je bila možna preko vodila RS232



 - [Nazaj na pregled računalnikov]({{site.base}}/racunalniki)