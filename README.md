# PrevOnto – igekötők ontológiája

A _PrevOnto_ (Preverb Ontology) 56 igekötő produktív jelentéseit és a jelentések közti kapcsolatokat mutatja be egy nyílt hozzáférésű ontológia formájában, amely gráfként ábrázolható (`PrevOnto.pdf`). Az ontológiáról az oldal alján feltüntetett publikációk nyújtanak részletes tájékoztatást.

### Az ontológia szerkezete

* Entitások (a gráfban csomópontok):
   * igekötők: zöld háttér = irányjelentéssel bíró igekötő, sárga háttér = irányjelentés nélküli igekötő
   * jelentések: áttetsző háttér

* Relációk (a gráfban élek):
   * szinonímia (rokonértelműség): ha egy jelentésből több igekötőbe vezet él, akkor az igekötők az adott jelentésük alapján szinonimák
   * antonímia (ellentétes jelentés): a jelentések közé húzott kétirányú nyíl jelzi
   * hipero- és hiponímia (hierarchikus viszony, az egyik jelentés magába foglalja a másikat): ennek jelzésére az egyirányú nyíl szolgál, amely a fölérendelt, általánosabb jelentésből az alárendelt, specifikusabb jelentés felé mutat

### Kiegészítő anyag

Az igekötők jelentéseit minden esetben példamondatok is illusztrálják, ezeket a `Preverb_senses_examples.docx` fájl tartalmazza.

### Licensz

Az ontológia a [GPL-3.0](https://github.com/kagnes/prevonto/blob/master/LICENSE) licensz alá tartozik. Amennyiben felhasználja az ontológiát, kérem, hogy hivatkozza az alábbi publikációk egyikét:

Kalivoda Ágnes (2021). Az igekötők produktív kapcsolódási mintái. _Argumentum 17._ p. 56-82. [https://doi.org/10.34103/ARGUMENTUM/2021/4](https://doi.org/10.34103/ARGUMENTUM/2021/4)

    @article{kalivoda2021,
        title = {Az igekötők produktív kapcsolódási mintái},
        journal = {Argumentum},
        volume = {17},
        year = {2021},
        pages = {56--82},
        author = {Kalivoda, {\'A}gnes},
        DOI = {https://doi.org/10.34103/ARGUMENTUM/2021/4}
    }

Kalivoda Ágnes (2021). _Igekötős szerkezetek a magyarban._ Doktori értekezés. Pázmány Péter Katolikus Egyetem, Bölcsészet- és Társadalomtudományi Kar, Nyelvtudományi Doktori Iskola. Budapest. _Megjelenés alatt._

	@phdthesis{kalivoda2021,
		address = {Budapest},
		type = {Doktori értekezés},
		title = {Igekötős szerkezetek a magyarban},
		school = {Pázmány Péter Katolikus Egyetem, Bölcsészet- és Társadalomtudományi Kar, Nyelvtudományi Doktori Iskola},
		author = {Kalivoda, {\'A}gnes},
		year = {2021}
	}

