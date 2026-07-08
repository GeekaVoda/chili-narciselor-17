---
{"dg-publish":true,"permalink":"/Știința Capsicum/🜜 Certificarea HPLC/","title":"Certificarea HPLC","tags":["botanica","stiinta","metodologie","hplc","scoville","capsaicina","masurare"],"dg-note-properties":{"title":"Certificarea HPLC","tags":["botanica","stiinta","metodologie","hplc","scoville","capsaicina","masurare"]}}
---


# Cum se măsoară cu adevărat iuțeala unui ardei


Când pe o pagină apare mențiunea *SHU necertificat HPLC* (High-Performance Liquid Chromatography) sau *estimare comunitară*, aceasta nu este o formulare de precauție excesivă — este o distincție cu consecințe reale pentru acuratețea informației. Înțelegerea diferenței dintre o valoare SHU obținută prin cromatografie de înaltă performanță și una estimată prin degustare sau declarație de cultivator este esențială pentru a citi corect orice fișă de ardei.

---

## De la degustare la cromatografie — o scurtă istorie

### Testul Scoville organoleptic (1912)

Wilbur Lincoln Scoville (22 ianuarie 1865 – 10 martie 1942) era farmacist la compania farmaceutică Parke-Davis din Detroit când a conceput, în 1912, o metodă de cuantificare a picantului ardeilor. Contextul era eminamente practic: capsaicina din ardei intra în compoziția unor preparate farmaceutice (tincturi, unguente rubefiante), iar variabilitatea între loturi făcea imposibilă standardizarea dozelor.

Metoda sa — *Scoville Organoleptic Test* — funcționa prin diluție succesivă: un extract alcoolic de ardei uscat era diluat progresiv în apă cu zahăr și prezentat unui panel de cinci degustători antrenați, până când cel puțin trei dintre ei nu mai percepeau senzația de iuțeală. Numărul de diluții necesare reprezenta valoarea în *Scoville Heat Units* (SHU): un ardei care necesita o diluție de 5.000 de ori înainte de a deveni neutru primea nota 5.000 SHU.

Metoda a servit timp de decenii ca singurul instrument disponibil. Limitele sale erau clare încă de la origine: depindea de sensibilitatea individuală a degustătorilor, de oboseala receptorilor (desensibilizare progresivă pe parcursul testului) și de condițiile variabile ale panelului. Studiile moderne estimează că variabilitatea unui panel de degustare antrenat ajunge la ±50% față de valoarea reală — un jalapeño de 5.000 SHU putea fi evaluat între 2.500 și 7.500 SHU de paneluri diferite.

### Cromatografia de înaltă performanță (HPLC)

Începând cu anii 1980, testul organoleptic a fost înlocuit treptat în contexte comerciale și științifice de **High-Performance Liquid Chromatography** — cromatografie de lichide de înaltă performanță. Astăzi, HPLC este metoda de referință internațională pentru cuantificarea capsaicinoidelor în ardei și produse derivate.

---

## Cum funcționează HPLC

Principiul de bază al cromatografiei lichide este separarea componentelor unui amestec prin migrarea lor diferențiată printr-o fază staționară solidă sub presiunea unui solvent (faza mobilă). HPLC utilizează o coloană metalică umplută cu particule solide foarte fine și o pompă de înaltă presiune care forțează solventul și proba prin coloană — de unde și denumirea alternativă *High-Pressure Liquid Chromatography*.

### Procesul pas cu pas

**1. Pregătirea probei**

Ardeii sunt uscați și măcinați. Capsaicinoidele sunt extrase cu un solvent organic — etanol sau acetonitril în protocoale standard — prin macerare sau extracție cu ultrasunete. Extractul filtrat constituie proba pentru analiză.

**2. Separarea cromatografică**

Proba este injectată în coloana HPLC. Componenții amestecului migrează prin faza staționară cu viteze diferite, în funcție de afinitatea lor chimică față de faza solidă. Capsaicina, dihidrocapsaicina și celelalte capsaicinoide se separă secvențial și ies din coloană la momente de timp distincte (*timp de retenție*).

**3. Detecția**

Compușii separați sunt detectați la ieșirea din coloană de un detector — cel mai frecvent UV (ultraviolet) la 280 nm sau fluorescență. Fiecare compus produce un semnal de intensitate proporțională cu concentrația sa — *cromatograma*.

**4. Cuantificarea**

Prin compararea cu standarde de referință calibrate (soluții de capsaicină pură de concentrație cunoscută), se calculează concentrația fiecărui capsaicinoid în proba de ardei, exprimată în mg/g sau ppm (părți per milion).

**5. Conversia în SHU**

Concentrația în capsaicinoide se convertește în Scoville Heat Units printr-un factor standardizat. Metoda de referință ASTA calculează întâi un indice de iuțeală în părți per milion (ppmH), ponderând compușii principali:

```
        arie(capsaicină) + 0,82 × arie(dihidrocapsaicină)
ppmH = ───────────────────────────────────────────────────
                        arie(standard)
```

Valoarea ppmH se convertește apoi în SHU prin înmulțire cu factorul definiției ASTA:

```
SHU = ppmH × 15
```

Unele protocoale folosesc factorul 16 în locul lui 15, valoare derivată din echivalarea capsaicinei pure cu aproximativ 16.000.000 SHU. Ambele convenții păstrează continuitatea cu datele istorice acumulate pe parcursul deceniilor de utilizare a scalei; diferența dintre ele explică o parte din variația valorilor SHU raportate pentru același soi.

**Notă privind coeficienții pe compus:** Nu toate capsaicinoidele au aceeași contribuție la iuțeală. [[Știința Capsicum/🜚 Nordihidrocapsaicina\|Nordihidrocapsaicina]] are un coeficient de echivalare SHU de aproximativ 9,3, față de circa 16,1 pentru capsaicină și [[Știința Capsicum/🜚 Dihidrocapsaicina\|dihidrocapsaicină]] (González-Zamora et al., 2015). Capsaicina și dihidrocapsaicina reprezintă împreună aproximativ 90% din conținutul total de capsaicinoide al unui ardei, motiv pentru care multe protocoale simplificate calculează SHU doar pe baza acestor doi compuși.

---

## Ce măsoară HPLC și ce nu măsoară

HPLC cuantifică cu precizie **concentrația chimică a capsaicinoidelor** într-o probă specifică, la un moment specific, dintr-un lot specific de ardei.

HPLC **nu măsoară** percepția subiectivă a iuțelii — care depinde de densitatea receptorilor TRPV1 la nivelul mucoasei individuale, de temperatura preparatului, de prezența grăsimilor sau proteinelor care leagă capsaicina, de experiența anterioară a consumatorului și de alți factori farmacologici individuali. Un ardei de 500.000 SHU nu este perceptibil ca de 10 ori mai iute decât unul de 50.000 SHU — relația dintre concentrația chimică și percepția subiectivă nu este liniară.

O altă limitare documentată: HPLC raportează frecvent valori SHU cu **20–40% mai mici** decât testul organoleptic pentru aceeași probă. Motivul este că testul Scoville original integra percepția tuturor compușilor care produc senzație de arsură, inclusiv unii care nu sunt capsaicinoide în sens strict. Cromatografia izolează doar capsaicinoidele identificate analitic.

---

## De ce variază valorile SHU între surse

Chiar și cu o metodă obiectivă ca HPLC, valorile SHU pentru același cultivar variază semnificativ între surse. Factorii documentați sunt:

**Condiții de cultivare:** Sol, temperatură, umiditate, stres hidric și luminozitate influențează sinteza capsaicinoidelor la nivel biochimic. Studiile USDA documentează variații de până la 30% SHU între recolte consecutive ale aceluiași cultivar în condiții diferite.

**Stadiul de maturitate la recoltare:** Conținutul de capsaicinoide crește pe măsura maturizării fructului, atingând maximum la maturitate completă și scăzând ușor după aceea (Siddiqui et al., 2013).

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

## Capsaicinoidele principale și potența lor relativă

| Compus | Abreviere | Potență relativă față de capsaicină | % din total capsaicinoide (tipic) |
|---|---|---|---|
| Capsaicină | CAP | 1,00 (referință) | ~50–70% |
| Dihidrocapsaicină | DHCAP | ~1,00 | ~20–30% |
| Nordihidrocapsaicină | NDHCAP | ~0,58 | ~5–7% |
| Homocapsaicină | HCAP | ~0,50 | ~1–2% |
| Homodihidrocapsaicină | HDHCAP | ~0,50 | ~1–2% |

Capsaicina și dihidrocapsaicina reprezintă împreună aproximativ 90% din conținutul total de capsaicinoide, motiv pentru care multe protocoale HPLC cuantifică doar acești doi compuși și calculează SHU pe baza lor.

---

## Bibliografie

- González-Zamora, A. et al. (2015). *Measurement of Capsaicinoids in Chiltepin Hot Pepper: A Comparison Study between Spectrophotometric Method and High Performance Liquid Chromatography Analysis*. Journal of Chemistry, 2015, Article 709150. <https://doi.org/10.1155/2015/709150>
- Al Othman, Z.A. et al. (2011). *Determination of capsaicin and dihydrocapsaicin in Capsicum fruit samples using high performance liquid chromatography*. Molecules, 16(10), 8919–8929. <https://doi.org/10.3390/molecules16108919>
- Orellana-Escobedo, L. et al. (2013). *Capsaicinoids content and proximate composition of Mexican chili peppers (Capsicum spp.) cultivated in the State of Chihuahua*. International Journal of Food Science & Technology, 48(8). <https://doi.org/10.1080/19476337.2012.716082>
- Collins, M.D., Wasmund, L.M. & Bosland, P.W. (1995). *Improved method for quantifying capsaicinoids in Capsicum using high-performance liquid chromatography*. HortScience, 30(1), 137–139.
- Wikipedia. *Scoville scale*. en.wikipedia.org. Accesat iulie 2026. <https://en.wikipedia.org/wiki/Scoville_scale>
- Wikipedia. *Wilbur Scoville*. en.wikipedia.org. Accesat iulie 2026. <https://en.wikipedia.org/wiki/Wilbur_Scoville>
- Wikipedia. *High-performance liquid chromatography*. en.wikipedia.org. Accesat iulie 2026. <https://en.wikipedia.org/wiki/High-performance_liquid_chromatography>
