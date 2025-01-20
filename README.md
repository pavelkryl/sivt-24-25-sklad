# sklad

Namodelujte v Pythonu datový model skladu zboží.

## Položka

Každá položka má:
- jednoznačný čárový kód (ne jako obrázek)
- nazev
- skladovou místnost
- cenu
- počet položek, které mám na skladě

## Místnost

Každá místnost má:
- kód místnosti
- rozlohu v metrech čtverečních

## Operace na skladu

Operace:
- založ novou položku
- naskladni položku (+ kusů)
- vyskladní položku (- kusů)
- najdi polozku "XYZ": vraci None když neexistuje
- kde je/v jaké místnosti se nachází položka s čárovým kódem "XYZ"?
- bonus: vrať skladovou místnost s největší rozlohou

Navrhněte model s ohledem na optimalitu první operace, tj. abych
byl schopen rychle najít konkrétní položku.

Ošetřete také stavy, které jsou chybové/nebezpečné -- například:
chci naskladnit položku, která neexistuje nebo chci vyskladnit
nesmyslně vysoký počet položek.

Při vašem návrhu se inspirujte testovacím kódem -- ušetří vám to
čas. Na konci zkuste testovací kód spustit a ověřte, že jste vše
správně naprogramovali.
