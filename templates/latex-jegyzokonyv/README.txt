A sablon használata:
A main.tex fájlt kell a fordítónak megadni, az hozza magával a többit. Pl texlive csomag esetén: pdflatex main.tex parancsot kiadva generálhatunk PDF-et.
Makefile használata: A Linuxon texlive használók make parancs segítségével is fordíthatnak.

A csomag tartalma:
- cite.tex: Ide írhatjuk be a hivatkozásokat, amiket az utolsó lapon fel is sorolunk és \cite{}-al a szövegben hivatkozni tudunk.
- content.tex: Itt írjuk meg magát a tartalmat (szöveg, képek).
- magyar.ldf : A nyelvi fájl, nem szerkesztjük.
- main.tex: A fő fájl. Ezt fordítjuk, illetve itt vannak deklarálva a több helyen is használt változók (név, tárgy, NEPTUN-kód, stb).
- titlepage.tex : Ez a dokumentum első oldala, amit ideális esetben nem szerkesztünk, mert minden szükséges információt elér a globális változóinkból.
- figures könyvtár: Ide pakoljuk be a képeket.


