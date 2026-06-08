---
{"dg-publish":true,"permalink":"/Capsicum/Certificarea HPLC/","tags":["botanica","stiinta","metodologie","hplc","scoville","capsaicina","masurare"],"dg-note-properties":{"tags":["botanica","stiinta","metodologie","hplc","scoville","capsaicina","masurare"]}}
---


# Cum se măsoară cu adevărat iuțeala unui ardei


Când pe o pagină apare mențiunea *SHU necertificat HPLC* (High-Performance Liquid Chromatography) sau *estimare comunitară*, aceasta nu este o formulare de precauție excesivă — este o distincție cu consecințe reale pentru acuratețea informației. Înțelegerea diferenței dintre o valoare SHU obținută prin cromatografie de înaltă performanță și una estimată prin degustare sau declarație de cultivator este esențială pentru a citi corect orice fișă de ardei.

---

## De la degustare la cromatografie — o scurtă istorie

### Testul Scoville organoleptic (1912)

Wilbur Lincoln Scoville (22 ianuarie 1865 – 10 martie 1942) era farmacist la compania farmaceutică Parke-Davis din Detroit când a conceput, în 1912, o metodă de cuantificare a picantului ardeilor. Contextul era eminamente practic: capsaicina din ardei intra în compoziția unor preparate farmaceutice (tincturi, unguente rubefaciente), iar variabilitatea între loturi făcea imposibilă standardizarea dozelor.

Metoda sa — *Scoville Organoleptic Test* — funcționa prin diluție succesivă: un extract alcoolic de ardei uscat era diluat progresiv în apă cu zahăr și prezentat unui panel de cinci degustători antrenați, până când cel puțin trei dintre ei nu mai percepeau senzația de iuțeală. Numărul de diluții necesare reprezenta valoarea în *Scoville Heat Units* (SHU): un ardei care necesita o diluție de 5.000 de ori înainte de a deveni neutru primea nota 5.000 SHU.

Metoda a servit timp de decenii ca singurul instrument disponibil. Limitele sale erau clare încă de la origine: depindea de sensibilitatea individuală a degustătorilor, de oboseala receptorilor (desensibilizare progresivă pe parcursul testului) și de condițiile variabile ale panelului. Studiile moderne estimează că variabilitatea unui panel de degustare antrenat ajunge la ±50% față de valoarea reală — un jalapeño de 5.000 SHU putea fi evaluat între 2.500 și 7.500 SHU de paneluri diferite.

### Cromatografia de înaltă performanță (HPLC)

Începând cu anii 1980, testul organoleptic a fost înlocuit treptat în contexte comerciale și științifice de **High-Performance Liquid Chromatography** — cromatografie de lichide de înaltă performanță. Astăzi, HPLC este metoda de referință internațională pentru cuantificarea capsaicinoizilor în ardei și produse derivate.

---

## Cum funcționează HPLC

Principiul de bază al cromatografiei lichide este separarea componentelor unui amestec prin migrarea lor diferențiată printr-o fază staționară solidă sub presiunea unui solvent (faza mobilă). HPLC utilizează o coloană metalică umplută cu particule solide foarte fine și o pompă de înaltă presiune care forțează solventul și proba prin coloană — de unde și denumirea alternativă *High-Pressure Liquid Chromatography*.

### Procesul pas cu pas

**1. Pregătirea probei**

Ardeii sunt uscați și măcinați. Capsaicinoizii sunt extrași cu un solvent organic — etanol sau acetonitril în protocoale standard — prin macerare sau extracție cu ultrasunete. Extractul filtrat constituie proba pentru analiză.

**2. Separarea cromatografică**

Proba este injectată în coloana HPLC. Componenții amestecului migrează prin faza staționară cu viteze diferite, în funcție de afinitatea lor chimică față de faza solidă. Capsaicina, dihidrocapsaicina și ceilalți capsaicinoizi se separă secvențial și ies din coloană la momente de timp distincte (*timp de retenție*).

**3. Detecția**

Compușii separați sunt detectați la ieșirea din coloană de un detector — cel mai frecvent UV (ultraviolet) la 280 nm sau fluorescență. Fiecare compus produce un semnal de intensitate proporțională cu concentrația sa — *cromatograma*.

**4. Cuantificarea**

Prin compararea cu standarde de referință calibrate (soluții de capsaicină pură de concentrație cunoscută), se calculează concentrația fiecărui capsaicin în proba de ardei, exprimată în mg/g sau ppm (părți per milion).

**5. Conversia în SHU**

Concentrația în capsaicinoizi se convertește în Scoville Heat Units prin înmulțire cu un factor standardizat. Formula de bază:

```
SHU = concentrație totală capsaicinoizi (ppm) × 16
```

sau echivalent:

```
SHU = concentrație capsaicină (mg/g) × 16.000–16.667
```

Factorul de conversie (~16) derivă din calibrarea istorică față de testul Scoville original: 1 ppm de capsaicină corespunde aproximativ 16 unități de diluție din metodologia Scoville. Această echivalare păstrează continuitatea cu datele istorice acumulate pe parcursul deceniilor de utilizare a scalei.

**Nota privind coeficienții pe compus:** Nu toți capsaicinoizii au aceeași potență. Nordicapsaicina are un coeficient de ~9,3 față de ~16,1 pentru capsaicină și dihidrocapsaicină (González-Zamora et al., 2015). Capsaicina și dihidrocapsaicina reprezintă împreună aproximativ 90% din conținutul total de capsaicinoizi al unui ardei, motiv pentru care mulți protocoale simplificate calculează SHU doar pe baza acestora două.

---

## Ce măsoară HPLC și ce nu măsoară

HPLC cuantifică cu precizie **concentrația chimică a capsaicinoizilor** într-o probă specifică, la un moment specific, dintr-un lot specific de ardei.

HPLC **nu măsoară** percepția subiectivă a iuțelii — care depinde de densitatea receptorilor TRPV1 la nivelul mucoasei individuale, de temperatura preparatului, de prezența grăsimilor sau proteinelor care leagă capsaicina, de experiența anterioară a consumatorului și de alți factori farmacologici individuali. Un ardei de 500.000 SHU nu este perceptibil ca de 10 ori mai iute decât unul de 50.000 SHU — relația dintre concentrația chimică și percepția subiectivă nu este liniară.

O altă limitare documentată: HPLC raportează frecvent valori SHU cu **20–40% mai mici** decât testul organoleptic pentru aceeași probă. Motivul este că testul Scoville original integra percepția tuturor compușilor care produc senzație de arsură, inclusiv unii care nu sunt capsaicinoizi în sens strict. Cromatografia izolează doar capsaicinoizii identificați analitic.

---

## De ce variază valorile SHU între surse

Chiar și cu o metodă obiectivă ca HPLC, valorile SHU pentru același cultivar variază semnificativ între surse. Factorii documentați sunt:

**Condiții de cultivare:** Sol, temperatură, umiditate, stres hidric și luminozitate influențează sinteza capsaicinoizilor la nivel biochimic. Studiile USDA documentează variații de până la 30% SHU între recolte consecutive ale aceluiași cultivar în condiții diferite.

**Stadiul de maturitate la recoltare:** Conținutul de capsaicinoizi crește pe măsura maturizării fructului, atingând maximum la maturitate completă și scăzând ușor după aceea (Siddiqui et al., 2013).

**Numărul și reprezentativitatea probelor:** Un test HPLC efectuat pe 3 fructe dintr-un lot și unul efectuat pe 50 de fructe din mai multe plante și locații pot returna valori diferite. Variabilitatea intra-varietală este reală și documentată.

**Metoda de extracție:** Solventul folosit, durata macerării și metoda de prelucrare a probei influențează randamentul extracției și implicit valoarea raportată.

**Uscarea probei vs. proba proaspătă:** Capsaicina se extrage mai eficient din ardei uscați față de ardei proaspeți (datorită interferenței umidității), iar majoritatea protocoalelor standardizate lucrează pe probă uscată. Același ardei proaspăt poate returna valori diferite față de cel uscat.

---

## Distincția practică pentru paginile acestui site

Pe paginile de ardei din acest site, valorile SHU sunt însoțite, unde este cazul, de una dintre următoarele calificări:

**Valoare certificată HPLC** — există un test de laborator publicat și verificabil, realizat pe probe reprezentative. Exemplu: 7 Pot Primo (1.473.480 SHU, test HPLC documentat de Troy Primeaux).

**Estimare comunitară** — valoarea circulă în comunitatea de cultivatori și degustători, bazată pe experiență repetată, dar fără test HPLC independent publicat. Exemplu: Primotalii Red (1.600.000–2.200.000 SHU, estimare comunitară neconfirmată HPLC la mai 2026).

**Interval botanic standard** — valoarea provine din literatura botanică sau din baze de date agricole de referință, bazată pe studii publicate pe cultivaruri reprezentative ale speciei/soiului. Exemplu: Ají Amarillo Cusqueño (30.000–50.000 SHU, interval confirmat în literatura de specialitate pentru *C. baccatum* var. *pendulum*).

Această distincție nu ierarhizează ardeii în funcție de valoarea lor — un ardei cu estimare comunitară nu este mai puțin real sau mai puțin picant decât unul cu certificare HPLC. Distincția indică doar **gradul de certitudine al datei numerice**.

---

## Capsaicinoizii principali și potența lor relativă

| Compus | Abreviere | Potență relativă față de capsaicină | % din total capsaicinoizi (tipic) |
|---|---|---|---|
| Capsaicină | CAP | 1,00 (referință) | ~47–55% |
| Dihidrocapsaicină | DHCAP | ~1,00 | ~35–42% |
| Nordihidrocapsaicină | NDHCAP | ~0,58 | ~5–7% |
| Homocapsaicină | HCAP | ~0,50 | ~1–2% |
| Homodihidrocapsaicină | HDHCAP | ~0,50 | ~1–2% |

Capsaicina și dihidrocapsaicina reprezintă împreună aproximativ 90% din conținutul total de capsaicinoizi, motiv pentru care multe protocoale HPLC cuantifică doar acești doi compuși și calculează SHU pe baza lor.

---

## Bibliografie

- Wikipedia. *Scoville scale*. en.wikipedia.org. Accesat mai 2026. <https://en.wikipedia.org/wiki/Scoville_scale>
- Wikipedia. *Wilbur Scoville*. en.wikipedia.org. Accesat mai 2026. <https://en.wikipedia.org/wiki/Wilbur_Scoville>
- Wikipedia. *High-performance liquid chromatography*. en.wikipedia.org. Accesat mai 2026. <https://en.wikipedia.org/wiki/High-performance_liquid_chromatography>
- González-Zamora, A. et al. (2015). Measurement of Capsaicinoids in Chiltepin Hot Pepper: A Comparison Study between Spectrophotometric Method and High Performance Liquid Chromatography Analysis. *Journal of Chemistry*, 2015, Article 709150. <https://doi.org/10.1155/2015/709150>
- Orellana-Escobedo, L. et al. (2013). Capsaicinoids content and proximate composition of Mexican chili peppers (*Capsicum* spp.) cultivated in the State of Chihuahua. *International Journal of Food Science & Technology*, 48(8). <https://doi.org/10.1080/19476337.2012.716082>
- Siddiqui, M.W. et al. (2013). Ascorbic acid, capsaicin and β-carotene content in Capsicum fruits. Citare internă prin: Springer Nature / *Food Production, Processing and Nutrition*.
- NCBI / PMC. *Determination of Capsaicin and Dihydrocapsaicin in Capsicum Fruit Samples using High Performance Liquid Chromatography*. PMC6264681. <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6264681/>
- Chromatography Today. *How Does the Scoville Scale Work for Spicy Peppers?* chromatographytoday.com. Accesat mai 2026. <https://www.chromatographytoday.com/news/liquid-chromatography/65/breaking-news/how-does-the-scoville-scale-work-for-spicy-peppers/54910>
- Spice Quest Labs. *Scoville Units: Why the Hype Doesn't Always Match the Lab*. spicequestlabs.com. Accesat mai 2026. <https://spicequestlabs.com/blogs/news/scoville-units-why-the-hype-doesnt-always-match-the-lab>
