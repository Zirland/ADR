# Údaje o nebezpečných látkách

1. Skript v pravidelných intervalech (momentálně jednou za hodinu vždy o půl) kontroluje, zda jsou na serveru k dispozici nové soubory formátu **XLSX**.
2. Každý soubor formátu XLSX je považován za vstupní data pro konverzi do XML.
3. Skript *předpokládá*, že soubor je správně formátován v předem dohodnuté struktuře. Neprovádí se kontrola správnosti dat.
4. Název souboru je *očekáván* ve formátu **XXXXX-XXX-X***.xlsx*, kde část názvu před tečkou je zpracován jako CAS číslo látky.
5. Položka **UN** je považována za povinnou položku a v tabulce musí mít vyplněnou hodnotu.
4. Výsledkem běhu skriptu je výstupní soubor formátu **XML**.
5. Po provedení konverze je zdrojový soubor XLSX ***SMAZÁN***.

# Nahrání vstupních souborů
1. Použitím tlačítka *Upload files* v nástrojové liště nad seznamem souborů je možno nahrát nové soubory.
2. Soubory lze na nahrávací okno přetáhnout myší nebo je možno soubory vybrat po stisku odkazu *choose your files*
3. Není nutno zadávat žádné další hodnoty nebo komentáře.
4. Nahrání souborů se dokončí stiskem tlačítka **Commit changes**.
