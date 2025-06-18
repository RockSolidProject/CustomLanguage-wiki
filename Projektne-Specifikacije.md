# Projektne specifikacije
## Namen tega projekta
Cilj projekta **RockSolid** je med drugim ustvariti tudi lasten domensko specifični jezik za delo z jezikom GeoJSON
### Skupine uporabnikov
* razvijalci, ki želijo enostavno risanje komponent na karti
* naprednejši uporabniki GeoJSON jezika, ki bi potrebovali naprednejše funkcionalnosti

***
## Opis rešitve
Projekt je razvit s pomočjo kotlin programskega jezika<br>
Omogoča: <br>
* prevajanje našega domensko specifičnega programskega jezika v GeoJSON

***
## Ključne funkcionalnosti
* Leksikalni analizator
  * omogoča pretvorbo kode v žetone (tokene) in sporoči napako ob nepravilnostih
* Sintaktični analizator
  * preverja ali je program pravilno semantično zapisan (upošteva gramatiko)
* Semantični analizator
  * prevede kodo v GeoJSON objekt in preveri relevantne napake

***
## Zahteve
### Sistemske zahteve
* Prevajalnik za [kotlin](https://kotlinlang.org/#) (priporočeno [Intellij IDEA](https://www.jetbrains.com/idea/))
### Strojne zahteve
#### Priporočene
* Ni preveč zahtevno strojno opremo
* **CPU**: 1 jedro
* **RAM**: 1 GB

***
## Glavne knjižnice in orodja
* Integrirane java knjižnice
* Pri nas je bilo uporabljeno orodje [Intellij IDEA](https://www.jetbrains.com/idea/) sicer pa zadostuje vsak prevajalnik za kotlin






