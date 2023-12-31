# Distribuce exam_app pro Android - manuální instalace přes .apk
Aplikace byla a je primárně vyvíjena pro zařízení s většími obrazovkami jako jsou tablety. I na menších zařízeních by aplikace měla z většiny fungovat (tzn. pokud něco nevidíte, tak by se k tomu mělo dát "doscrollovat"), ale tato optimalizace prozatím nepatří mezi priority vývoje.

## Jakou verzi?
Pokud si nejste jistí, ze které složky .apk soubor stahovat, tak:
1. Architektura jde zjistit v nastavení zařízení (nejčastějsi záložka "O zařízení", "Systém" apod.)
2. Rule-of-thumb, novější zařízení jsou většinou arm64, takže nejdříve zkoušet tuto složku

## Instalace
1. Proklikejte se až na stránku s "kódem" .apk souboru (složka -> soubor .apk)
2. Stáhnout (přes klasické 3 tečky)
3. Přemístěte do paměti telefonu
4. Klikněte na telefonu na soubor
5. "Install/Instalovat"
6. Google Play Protect může hlásit "Unsafe app" -> klikněte "More details/Více možností" -> "Install anyway/Přesto instalovat"
7. Ikonka aplikace pod jménem exam_app by se měla objevit na domovské stránce

## Testované verze
* Android 9 (MIUI 11)
* Android 10 (MIUI 12)
* Android 11 (MIUI 14)
