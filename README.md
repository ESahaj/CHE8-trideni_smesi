# Laboratoř směsí

Responzivní obrázková hra pro procvičování homogenních a heterogenních směsí. Obsahuje 32 obrázků, výběr druhu heterogenní směsi, barevné vyhodnocení, vysvětlení a závěrečné skóre.

## Spuštění na GitHub Pages

1. Rozbal stažený ZIP.
2. Vytvoř na GitHubu nový veřejný repozitář, nebo otevři existující repozitář pro tuto hru.
3. Přes **Add file → Upload files** nahraj soubor **index.html** a případně **.nojekyll** a tento README přímo do hlavní složky repozitáře. Potvrď **Commit changes**.
4. Otevři **Settings → Pages**.
5. V části **Build and deployment** zvol **Source: Deploy from a branch**.
6. Vyber větev **main**, složku **/(root)** a klikni na **Save**.
7. Po dokončení zveřejnění najdeš odkaz na hru v části **Settings → Pages**. První zveřejnění může trvat několik minut.

Pokud má repozitář hlavní větev pojmenovanou jinak, vyber její skutečný název.

Obvyklá adresa je https://TVUJ-UCET.github.io/NAZEV-REPOZITARE/ .

Pokud už v repozitáři existuje jiný soubor index.html, jeho nahrazení změní úvodní stránku. Pro tuto hru je nejjednodušší použít samostatný repozitář.

## Bez internetu

Soubor **index.html** lze otevřít přímo v prohlížeči. Obsahuje všechny obrázky, styly i logiku hry a nevyžaduje instalaci, přihlášení ani připojení k internetu.

## Ovládání

Každé kolo vybere 15 náhodných směsí z 32, bez opakování v rámci kola.

Nejprve vyber homogenní nebo heterogenní směs. Po správné volbě heterogenní směsi se zobrazí výběr: suspenze, emulze, pěna, aerosol – dým nebo aerosol – mlha.

Chybná možnost zčervená a připočte se jeden chybný pokus. Správná odpověď se neoznačí ani nevysvětlí, dokud ji hráč sám nezvolí. Už vyřazenou chybnou možnost nelze znovu stisknout. Ostatní možnosti zůstávají aktivní.

Po správné volbě se tlačítko zbarví zeleně. Oba výběry i chybné volby zůstávají viditelné až do kliknutí na Další. Tlačítko Další se zpřístupní až po správném vyřešení celé karty.

Hra průběžně zobrazuje počet chybných pokusů. Na konci ukáže součet chyb a počet směsí vyřešených bez chyby. Nová hra vylosuje dalších 15 směsí a vynuluje výsledky.
