NÁGL ELEKTRO - STATICKÝ WEB
============================

Tento balíček obsahuje kompletní statický web v podobě HTML souborů.

JAK TO POUŽÍT:
1. Rozbal ZIP do libovolné složky.
2. Otevři ji ve Visual Studio Code (File → Open Folder).
3. Pro PROHLÉDNUTÍ stačí dvojklikem otevřít kterýkoli .html soubor v prohlížeči.
   Doporučuju ale použít rozšíření "Live Server" ve VS Code:
   - klik pravým na index.html → "Open with Live Server"
4. Pro NAHRÁNÍ NA WEB nahraj všechny soubory (.html + složku assets/) na 
   FTP libovolného webhostingu. Žádný build proces není potřeba.

CO BALÍČEK OBSAHUJE:
- index.html ............... Úvodní stránka
- elektroinstalace.html .... Služba: Elektroinstalace
- tepelna-cerpadla.html .... Služba: Tepelná čerpadla
- klimatizace.html ......... Služba: Klimatizace
- kamerove-systemy.html .... Služba: Kamerové systémy
- revize-elektro.html ...... Služba: Revize elektro
- o-mne.html ............... O firmě a Kamilu Náglovi
- reference.html ........... Ukázkové reference
- kontakt.html ............. Kontakt + formulář (odešle e-mail klientovi)
- blog.html ................ Přehled blogu
- blog-*.html .............. 5 článků blogu
- assets/ .................. Všechny obrázky

STYLOVÁNÍ:
Používá Tailwind CSS přes CDN (načítá se z internetu). Vše stylováno inline,
žádný build nepotřebuješ. Vlastní fonty (Inter) také z Google Fonts CDN.

Pro produkci doporučuju:
- vyměnit telefon +420 777 777 777 a e-mail info@naglelektro.cz za skutečné
- nahradit obrázky vlastními fotkami
- formulář na /kontakt.html nahradit serverovým řešením (např. Formspree, 
  Web3Forms) místo mailto: odkazu
