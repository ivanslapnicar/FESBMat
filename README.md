# FESBMat

Jupyter bilježnice matematičkih predmeta na [FESB-u](https://www.fesb.unist.hr/).

## Korištenje

Materijali su pisani kao [Jupyter](http://jupyter.org/) ([IJulia](https://github.com/JuliaLang/IJulia.jl)) bilježnice (engl. _notebooks_). Bilježnice možete koristiti na sljedeća tri načina.

### Korištenjem preglednika

Unutar svojeg preglednika bilježnice možete pregledati pomoću [Jupyter notebook viewera](http://nbviewer.jupyter.org/) na sljedećoj [poveznici](http://nbviewer.ipython.org/url/github.com/ivanslapnicar/FESBMat/tree/master/src/).

###  Lokalno preuzimanje i pregled na vlastitom računalu
* Instalirajte [Julia-u](https://julialang.org/downloads/) i [Jupyter](http://jupyter.org/install.html).
* Preuzmite bilježnice (repozitorij) korištenjem `git` naredbe:
```
git clone https://github.com/ivanslapnicar/FESBMat.git
```
Ako niste upoznati s `git` alatom možete pogledati GitHubove [stranice za pomoć](https://help.github.com/articles/set-up-git/) ili direktno preuzeti bilježnice (repozitorij) na sljedećoj [poveznici](https://github.com/ivanslapnicar/FESBMat/archive/master.zip).    
* Nakon izvršavanja naredbe (kloniranja) ili direktnog preuzimanja bilježnice se nalaze u direktoriju `Numericka_analiza/src` pa ih možete pregledavati na Vašem računalu.

### Korištenjem JuliaBox-a

Bilježnice možete izvršavati na Amazon Cloudu koristeći [JuliaBox](https://juliabox.com/).
* Idite na https://juliabox.com i prijavite se sa svojim LinkedIn, GitHub ili Google računom.
* Na izbornoj traci odaberite opciju `Sync`.
* U sekciji _Git Repositories_ u polje __Git Clone URL__ unesite adresu `https://github.com/ivanslapnicar/FESBMat`.
* Provjerite da je polje __Branch__ postavljeno na _master_ (to je vjerojatno već automatski učinjeno).
* Provjerite da je __JuliaBox Folder__ postavljen na _FESBMat_.
* Pritisnite __+__ iz retka akcija uz unesene podatke za dodavanje repozitorija.
* Pritisnite zaokruženu strelicu okrenutu prema dolje za sinhronizaciju s repozitorijem.
* Na izbornoj traci odaberite opciju `Jupyter`.
* Po potrebi osvježite listu pritiskom na pripadajuću ikonu iznad popisa datoteka.   
Sada imate naveden direktorij `FESBMat` u čijem se poddirektoriju`src` nalaze same bilježnice.

Konfiguriranje ovog pristupa je prikazano i YouTube [videom](https://www.youtube.com/watch?v=2gzctyr4pPk).
