# Dokumentacija izvedenih lastnosti
Dokumentacija zajema podrobnosti o implementaciji posameznih funkcionalnosti (task), opisanih in vodenih v sistemu JIRA.
***
## ROCK-52 - Leksikalni analizator
**Namen:** Pretvarjanje vsebine programa v žetone
**Način implementacije:**
* hrani se trenutno stanje programa
* glede na naslednji vhodni znak se v podani tabeli izvede akcija - spremeni se trenutno stanje programa in po potrebi se doda nov žeton
**Način uporabe:** uporabnik pošlje podatkovni tok v izdelan razred, ta pa predela tok in izvozi žetone

***
## ROCK-92 - sintaktična analizator
**Namen:** Preverjanje pravilnosti programa
**Način implementacije**
* s pomočjo gramatike
![gramatika](https://github.com/user-attachments/assets/74df2fac-e95f-4a5f-8c98-c79620870635)
* osnovna implementacija rekurzivnega sintaktičnega razpoznavalnika
**Način uporabe:** listo žetonov se pošlje v implementirani razred, ki nato preveri ali je program sintaktično pravilen ali ne.

***
## ROCK-94 - semantični prevajalnik
**Namen:** Semantična interpretacija programa
**Način implementacije** 
* s pomočjo semantičnih funkcij
* ideja je uporaba funkcij višjega reda
**Način uporabe:** listo žetonov pridobljeno z leksikalnim analizatorjem pošljemo v novonarejen razred

***
## ROCK-106 - pretvorbeni objekti v geoJSON
**Namen:** dodajanje funkcionalnosti samemu prevajalniku
**Način implementacije**
Semantični analizator ima implementirano začetno listo funkcij, ki jih podpira, tem funkcijam se doda nove.
**Način uporabe: ** V programu lahko sedaj kličemo nove implementirane funkcije kot so door, window, ...

***
ROCK-158 - dodajanje AST dreves
**Namen:** izpis dreves klicov funkcije
**Način implementacije:**
posebni razredi
**Način uporabe:**
TODO


