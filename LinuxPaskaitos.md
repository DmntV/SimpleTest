#Paskaita 1

##Kompiuterinės sistemos

XXI amžiuje, beveik visi kas nulaiko rankose telefoną, kasdieną naudojasi kompiuteriais ir jų sistemomis, tačiau tikrai ne visi žino kas yra kompiuteris ar kas sudaro kompiuterių sistemą. Aišku, daug kas gali tiesiog perskaitytų wikipedijos puslapį, ten rastų atsakymą, jog kompiuterių sistema tai: „iš vieno ar daugiau kompiuterių, išorinių įrenginių ir programinės įrangos sudaryta visuma, atliekanti duomenų apdorojimą.” Tačiau norint suprasti kas iš tiesų yra kompiuterinė sistema, reikia į kiekvieną apibrėžimo aspektą pažvelgti atidžiau.

Pirmoji ir neatsiejama kompiuterio dalis yra procesorius (*Angl.* ***Processor*** *nors tikslesnis pavadinimas yra* ***CPU – Central processing unit***). Jis atlieka: įprastas matematines, logines, įvesties bei išvesties operacijas, taip pat paskirsto kitiems kompiuterio elementams skirtas komandas. Kita neatsiejama kompiuterio ir procesoriaus dalis yra atmintis. Norint, kad CPU galėtų tinkamai atlikti savo darbą, jai reikia kažkur saugoti informaciją. Procesorius dažniausiai turi integruotą atmintį vadinamą spartinančiąją atmintinę (*Angl.* ***Cache***), o pati greičiausia jos dalis vadinama registru (*Angl.* ***Registry***), kuriame yra saugomi pagrindinių instrukcijų adresai.

Procesorius priklauso aparatinei įrangai (*Angl.*  ***Hardware***) ir yra viską jungiančios motininės plokštės (*Angl.* ***Motherboard***) dalis. Jai dar priklauso laisvosios prieigos atmintis (*Angl.* ***RAM – Random-accsess memory***) kurią naudoja procesorius, pastovioji atmintis (*Angl.* ***ROM – Read-only memory***), joje saugoma BIOS, kuri pasileidžia vartotojui paleidus kompiuterį, ji atsakinga už operacinės sitemos paleidimą. Taip pat aparatinei įrangai priklauso ir įvesties (*Angl.* ***Input***) ir išvesties (*Angl.* ***Output***) įrenginiai. Patys paprasčiausi įvesties įrenginių pavyzdys yra klaviatūra (*Angl.* ***Keyboard***),  šie įrenginiai leidžia vartotojui siųsti informaciją procesoriui kuris ją interpretuoja ir atlieka atitinkamus veiksmus. Geras išvesties įrenginio pavyzdys yra vaizduoklis (*Angl.* ***Monitor***), jis konvertuoja kompiuterio signalus į žmonėms suprantamą formą, šiuo atveju – vaizdą. Monitoriui veikti reikalinga vaizdo plokštė (*Angl.* ***GPU – Graphics processing unit***). Dar aparatinei įrangai priklauso ilgalaikės atminties laikmenos. Pagrindiniai ir įprastai sutinkami atminties laikmenų tipai yra standusis diskas ir puslaidininkis diskas (*Angl.* ***HDD – Hard disk drive*** *ir* ***SSD – Solid-state drive***). Jie skiriasi gana daug kuo, tačiau pagrindinis skirtumas yra tas, jog puslaidininkis diskas veikia greičiau, bet yra brangesnis už standujį diską.

Kitaip nei aparatinė įranga, programinė įranga (*Angl.* ***Software***) nėra daiktas, tai komandų ar kompiuterinių instrukcijų rinkinys. Ji skirstoma į: programinę aparatinę įrangą (*Angl.* ***Firmware***) skirtą aparatinės įrangos žemo lygio kontrolei, naudingas ar žalingas programas (*Angl.* ***Applications*** *ir* ***Malware***) ir operacines sistemas (*Angl.* ***OS – Operating system***).

Kompiuteriai gali būti sujungti į sistemas susietas fiziniu ar internetiniu duomenų tinklu (*Angl.* ***Computer cluster, grid or Cloud computing***) , taip pagreitinamas jų darbas.

>386 žodžiai.

###Šaltiniai (paskutinį kartą žiūrėti 2019-11-03):
* Anglų–lietuvių kalbų kompiuterijos žodynėlis: http://www.likit.lt/en-lt/;
* Wikipedia puslapis „Software“: https://en.wikipedia.org/wiki/Software;
* Wikipedia puslapis „Computer hardware“: https://en.wikipedia.org/wiki/Computer_hardware;
* Apie Cache memory: https://www.sciencedirect.com/topics/computer-science/cache-memory;
* Kas yra kompiuteris, jų sistema (dalis informacijos yra iš pateiktuose puslapiuose esančių nuorodų): http://ecomputernotes.com/fundamental/introduction-to-computer/what-is-computer;
https://www.explainthatstuff.com/howcomputerswork.html;
https://lt.wiktionary.org/wiki/kompiuteri%C5%B3_sistema;
* Kas yra procesorius: https://whatis.techtarget.com/definition/processor.
#Paskaita 2
##Teksto redagavimas terminale su programa emacs
Internete galima rasti daug įvairių teksto redagavimo programų skirtų Unix operacinėms sistemoms. Dažniausiai jų ieškoti nė nereikia, nes daugelis Unix operacinių sistemų turi numatytą teksto redaktorių, pavyzdžiui CentOS 7 turi numatytą (*Angl.* ***Default***) „vi“ teksto redaktorių. Tačiau dauguma numatytųjų redaktorių yra gana paprasti ir priklausomai nuo užduoties sudėtingumo, jų gali nepakakti. Vienas iš galingesnių ir praktiškesnių teksto redaktorių yra „emacs“, tačiau norint juo naudotis yra pravartu, o kartais būtina mokėti jo komandas.
>***Pagrindinės komandos***: 

* **C** reiškia* **Control** *arba* **Ctrl** *mygtuką*;
* **-** *reiškia kad mygtukus reikia spausti vienu metu, o „ “ reiškia jog niekas nepaspausta*;
* **M** *reiškia* **Alt** *arba* **Esc** *mygtuką*;
* **RET** *reiškia grįžti* (*Angl.* ***Return***) *ir tai yra mygtukas* **Enter**;
* **C-g** atšaukia operaciją;
* **C-x C-f** leidžia ieškoti failo arba sukuria naują failą buferyje (*Angl.* ***Buffer***), po komandos reikia įrašyti failo pavadinimą. Buferis yra emacs langas, kuriame redaguojamas failas;
* **C-x C-r** atidaro failą tik skaitymui (*Angl.* ***Read-only***);
* **C-x C-s** išsaugo failą;
* **C-x C-w** išsaugo failą nauju vardu;
* **C-x i** įterpia failą ties kursoriumi;
* **C-x b** sukuria naują buferį arba pereina prie jau esamo buferio;
* **C-x C-b** buferių lentelė;
* **C-x C-c** uždaro emacs.
>***Judėjimas faile:***
* **C-n** perkelia kursorių į sekančią eilutę;
* **C-p** perkelia į ankstesnę eilutę;
* **C-f** perkelia kursorių vieną simbolį į priekį;
* **C-b** perkelia kursorių vieną simbolį atgal;
* **M-f** perkelia kursorių vieną žodį į priekį;
* **M-b** perkelia kursorių vieną žodį atgal;
* **C-a** perkelia kursorių vieną eilutę į priekį;
* **C-e** perkelia kursorių vieną eilutę atgal;
* **M-a** perkelia kursorių vieną sakinį į priekį;
* **M-e** perkelia kursorių vieną sakinį atgal;
* **C-v** nuleidžia puslapį;
* **M-v** pakelia puslapį;
* **M-<** perkelia kursorių į failo pradžią;
* **M->** perkelia kursorių į failo pabaigą.
>***Teksto redagavimas:***
* **C-Space** arba **C-@** padeda žymeklį, tada reikia perkelti kursorių ir vėl panaudoti vieną iš komandų, taip pažymimas tekstas tarp dviejų žymeklių. Komandą panaudojus trečią kartą teksto pažymėjimas nuimamas;
*  **C-x h** pažymi visą aktyvų buferį;
* **M-h** pažymi paragrafą su kursoriumi;
* **E-w** kopijuoja tekstą;
* **C-w** iškerpa tekstą;
* **C-y** įklijuoja tekstą.
* **C-x u**arba **C-_** arba **C-/** grįžta vieną veiksmą atgal;
* **C-g C-_** arba **C-x C-u** grįžta vieną veiksmą į priekį jei įmanoma;
* **C-s** atlieka įvedamo žodžio paiešką tekste į priekį;
* **C-r** atlieka įvedamo žodžio paiešką tekste atgal nuo kursoriaus.

>390 žodžių.

###Šaltiniai (paskutinį kartą žiūrėti 2019-11-03):
* Kaip naudotis emacs redaktoriumi Linux sistemose: https://www.digitalocean.com/community/tutorials/how-to-use-the-emacs-editor-in-linux;
* Emacs komandų lentelė: https://www.ast.cam.ac.uk/~vasily/idl/emacs_commands_list.html.

#Paskaita 3
#Paskaita 4
#Paskaita 5
#Paskaita 6
