# 🏰 Tower Defense – Java Desktop Game

Tento projekt je strategická hra typu Tower Defense vytvorená v jazyku **Java**. Aplikácia sa zameriava na implementáciu hernej logiky, objektovo orientovaný návrh a prácu s grafickým rozhraním Swing/AWT.
- projekt bol realizovaný ako semestrálna práca v 1. ročníku bakalárskeho štúdia na predmet Informatika 1.

## 🛠️ Použité technológie
- **Jazyk:** Java

## 🏗️ Technická implementácia a architektúra

Projekt demonštruje kľúčové princípy vývoja desktopových aplikácií a hier:

- **Objektovo orientované programovanie (OOP):**
  - **Dedičnosť:** Využitie základných tried pre spoločnú logiku nepriateľov a veží, čo umožňuje ľahké rozširovanie o nové typy jednotiek.
  - **Zapuzdrenie:** Každá entita (veža, nepriateľ, projektil) si spravuje svoje vlastné atribúty ako zdravie, dostrel či poškodenie.
- **Herná slučka (Game Loop):** Implementácia cyklu, ktorý v reálnom čase aktualizuje pozície nepriateľov, deteguje kolízie a prekresľuje hernú plochu.
- **Matematika v hre:** Výpočty vzdialeností pre automatické zameriavanie nepriateľov v dosahu veží.
- **Dlaždicový systém (Grid system):** Návrh mapy pomocou súradnicového systému, ktorý definuje cestu nepriateľov a miesta pre výstavbu veží.
- **Správa Assetov:** Programové načítavanie a vykresľovanie obrázkov (sprites) pre herné objekty a pozadie.

## 🚀 Funkcie hry
- **Ekonomický systém:** Získavanie hernej meny za zneškodnenie nepriateľov a jej následné investovanie do obrany.
- **Vlny nepriateľov:** Logika postupného generovania nepriateľov so zvyšujúcou sa obtiažnosťou.
- **Interaktívne menu:** Používateľské rozhranie pre výber a umiestňovanie veží na mapu.
