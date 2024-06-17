Volební skraper

O co jde v projektu?
Tento skript umožňuje získat výsledky parlamentních voleb z roku 2017 pro konkrétní okres z této webové stránky (vyberte si okres ve sloupci Výběr obce) a uložit je do CSV souboru.

Jak na to?
Před spuštěním projektu si nainstalujte potřebné knihovny uvedené v souboru requirements.txt. Skript spusťte z příkazového řádku pomocí následujícího příkazu:

python projekt_3.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2101" vysledky_kraj.csv

Výstupem bude soubor .csv s výsledky voleb pro daný okres.

Jak to vypadá v praxi?

Například volby do Poslanecké sněmovny Parlamentu České republiky:
1. Odkaz: -> [https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2101](https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2101)
2. Název výstupního souboru -> vysledky_kraj.csv
