# Egészségügyi informatikai rendszerek biztonsága

> ajánlott irodalom: Szathmári Sándor kazohinia

Jegyszerzés: évközi jegy / a szorgalmi időszak utolsó órarendi találkozásának utolsó percéig

## EA1
Érdekesség: [úniós jog minden úniós nyelven](https://eur-lex.europa.eu/homepage.html?locale=hu)

(Simpson paradoxon)[https://hu.wikipedia.org/wiki/Simpson-paradoxon]

feladat: https://miau.my-x.hu/miau/ex-cel-atlon/kuratorium.docx


# EA2

https://miau.my-x.hu/miau/273/naiv_optimalizalt_verziok2.xlsx

# EA3 ~ egészségügyi adatkezelés

Alapvető elentmondás: páciens adatait védenünk kell, de az orvosnak meg mindne adat kell.

Klasszikus szereplők:
- háziorvos
- kórház
- gyógyszertár

más szereplők:
- telemedicína
- magán ellátóhelyek
- okosóra/fitnesszkarkötő/stb

Mindre vonatkozik jogszabály, hogy mit lehet és mit nem lehet kezdeni az adatokkal. Az adatok elektroniksra való leképezése külön probléma, mert lehet strukturált és strukturáltaltan adat.

- [BNO](https://hu.wikipedia.org/wiki/BNO-10_k%C3%B3dok_list%C3%A1ja) - betegségek nemzetközi osztályozása
  - régi kód: 4 karakter vagy országonként lehet 5
  - U kódok a saját jelölésre
  - J10xx - J11xx influenza 
- ICD10
- ICD11 - már teljesen elektronikusra tervezett rendszer, nem szempont a könyvbe szerkeszthetőség, legyen egy nemzetközi sztenderd a kutatások egyesítésére. 
- [OENO](http://finanszirozas.neak.gov.hu/szabalykonyv/index.asp?mid=1&pid=29) kódrendszer - az eljárásokat osztályozza és követi az orvostan fejlődését
- [SNOMED 3.5 ver](https://datadictionary.nhs.uk/attributes/snomed_version.html)ziója 11 dimenzió és 157000 bejegyzés. Tisztán gépek sázmára készült adatbázis
- [HL7](https://en.wikipedia.org/wiki/Health_Level_7) - az ISO OSI modell 7. applikációs rétegéja a fejlesztéseit. 55+ ország tagja A napi klinikai gyakorlatot és az egészégüggyi menedzsmentet közti össze.
- [IHE](https://wiki.ihe.net/index.php/IHE_Format_Codes) - a finanszírozás szempontjából veszi az orvosi  krédéseket.

Adatvédelem
-adatbiztonság részei:
  - bizalmasság
  - integritás
  - renelkezésre állás
  - adinisztráció
  - bizonyosság
- adatvédelmi irányelvek
- authorizáció
- hozzájárulás mendzsment
- kriptográfia
- anonimizálás, pszeudomizálás

- authentikáció: ki vagyok?
- authorizáció: mit tehetek meg?
- hozzájárulás menedzsment: hozzájárulás irányelv


Adatkezelési irányelvek:
- érintet jogai
- felhasználási jogok
- beteg jogok: önrendelkezés, ellátsá visszautasítása, *tájékoztatás*, *orvosi titoktartás* 

Betegek önrendelkezésének tiszteletben tartása:
- milyen nemű/ vallású/stb orvos nyúlhat hozzá
- mit tehet a testével
- az adatok továbbításának jogi követelményei

# EA4
> Van-e értelme védeni jelentéktelen  adatokat?


**free datasetek:**
- https://mlcourse.ai/
- https://data.nasdaq.com/search?filters=%5B%22Free%22%2C%22Europe%22%5D
- https://datasetsearch.research.google.com/
- https://www.dataquest.io/blog/free-datasets-for-projects/

*házi: kitalálni egy olyan attribútumot ami érvényes mindegyik bemeneti adatra*

# EA5
https://miau.my-x.hu/mediawiki/index.php/OE_egeszsegugyi_informatikai_rendszerek_biztonsaga#2021.10.07.
> az ár a döntési rendszer inputja
> - https://miau.my-x.hu/msc/kuratorium/kuratorium_2021_iofn.xlsx
> - https://miau.my-x.hu/mediawiki/index.php/OE_3333 
> - https://miau.my-x.hu/mediawiki/index.php/OE_egeszsegugyi_informatikai_rendszerek_biztonsaga#2021.10.07.

https://miau.my-x.hu/msc/kuratorium/kuratorium_2021_iofn_v2.xlsx 

# EA6
a jogszabályokat nem lehet áttekinteni amíg nem következetesek, 

# EA7
https://miau.my-x.hu/mediawiki/index.php/OE_egeszsegugyi_informatikai_rendszerek_biztonsaga#2021.10.21.
