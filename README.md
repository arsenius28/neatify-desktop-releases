# Neatify Admin — instalátory

Podepsané instalátory desktopové administrace Neatify.

Repozitář obsahuje **pouze sestavené instalátory a manifest aktualizací**.
Zdrojový kód aplikace je privátní.

## Aktualizace

Nainstalovaná aplikace si novou verzi najde a nabídne sama. Každý balíček je
podepsaný klíčem, jehož veřejná část je zapečená v aplikaci — nepodepsanou
nebo cizí aktualizaci odmítne ještě před stažením.

## Instalace

Stáhni `Neatify-Admin-<verze>-setup.exe` z nejnovějšího vydání.

Windows může při první instalaci zobrazit varování SmartScreenu, protože
instalátor zatím nemá Authenticode certifikát. Podpis aktualizací na tom
nezávisí a funguje i bez něj.

Aplikace se přihlašuje **heslem aplikace** z WordPressu, které se ukládá do
systémového trezoru. Běžné heslo k účtu do ní nepatří.