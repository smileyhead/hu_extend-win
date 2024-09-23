# Kiterjesztett magyar billentyűzetkiosztás Windowsra
Az intermatrix.hu kiterjesztett magyar billentyűzetkiosztásának szerkesztett és Windowsra átültetett verziója.

![A kiterjesztett magyar billentyűzetkiosztás](https://github.com/smileyhead/hu_extend-win/blob/main/billentyuk.png?raw_true)

2015 végén az intermatrix.hu írt egy cikket a számítógépeken ma is használatos magyar billentyűzetkiosztás hiányosságairól. A cikket [mindenképpen ajánlom elolvasni](https://intermatrix.hu/hu-keyboard) ([archivált változat](https://web.archive.org/web/20220119112820/https://intermatrix.hu/hu-keyboard)), de íme egy rövid idézet, ami kiemeli a lényeget:
> A magyar billentyűzetkiosztás a mai napig nem csak a speciálisabb igényeket nem tudja kielégíteni, de az alapvető magyar helyesírás és központozás szabályait sem. A gondolatjel (–), a három pont (…), a magyar idézőjel páros („ ”), a másodlagos magyar idézőjel páros (» «) csak karaktertáblán keresztül beszúrással érhető el, míg más szimbólumok ismétlődnek (e, E, <, >, í, Í, §, N, Ł, Đ, &, ÷, °), továbbá megtalálhatóak olyanok, melyek a legkevésbé szükségesek a magyar nyelvben (ł, Ł, ŧ, Ŧ, ø, Ø, þ, Þ, đ, Đ, Ŋ, ħ, Ħ).

A cikk szerzője felötlött egy olyan billentyűzetkiosztást, ami ezeket a problémákat megoldja és a maradék helyet kihasználva még temérdek új karakterrel is kibővíti a klaviatúrát. A cikk azt is leírja, hogy Linuxon mi hogyan használhatjuk ezt a kiosztást, viszont a Windows kicsit háttérben marad. Ezt orvoslandó, a [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) segítségével átültettem az ötletet Windowsra, hogy ezen az operációs rendszeren is bárki használhassa.

## Különbségek
- Az MKLC hiányossága, hogy a numerikus billentyűzet kiosztását nem lehet vele módosítani, így az eredeti cikkben szereplő nyílkarakterek és egyéb szimbólumok begépelése sajnos nem lehetséges.
- Az eredeti módosított kiosztás nem tartalmazott amerikai idézőjeleket, viszont kétszer is tartalmazta a brit idézőjeleket (<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> és <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd>, illetve <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>J</kbd> és <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>H</kbd> billentyűkombinációk alatt). Ezen módosítottam, így ebben a változatban lehetséges amerikai idézőjeleket is beilleszteni az <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>H</kbd> és <kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>J</kbd> billentyűkkel. Mivel az amerikai és magyar záró idézőjel ugyanaz a karakter (”), ez azt is jelenti, hogy a <kbd>J</kbd> billentyű az <kbd>AltGr</kbd> nyomvatartása mellett, a <kbd>Shift</kbd> billentyűtől függetlenül ugyanazt a szimbólumot illeszti be.

## Letöltés és telepítés
A kiosztást [ezen a hivatkozáson](https://github.com/smileyhead/hu_extend-win/releases/latest/download/hu_ext.zip) töltheti le.

A telepítéshez csomagolja ki a tömörített mappát és futtassa a „setup.exe” fájlt! A billentyűzetkiosztás ezután azonnal telepítve lesz. Az aktív billentyűzetkiosztás kiválasztásához a nyelvi eszköztárat használhatja, ami a képernyő jobb alsó sarkában, általában HUN-jelzéssel jelenik meg. Ha szeretné, eltávolíthatja az alapértelmezett magyar billentyűzetkiosztást a Windows nyelvi beállításai alatt.

## Linux
Ha kívánja a szerkesztett kiosztásomat Linuxon használni, kövesse az eredeti útmutatót az [intermatrix.hu-n](https://intermatrix.hu/hu-keyboard) ([archivált változat](https://web.archive.org/web/20220119112820/https://intermatrix.hu/hu-keyboard)), de amikor ahhoz a részhez jut, ahol a `hu_extend` fájlt kell létrehoznia, az ott leírtaktól eltérően töltse fel [ezzel a tartalommal](/hu_extend)!
> [!NOTE]
> A linuxos [hu_extend](/hu_extend) fájl csak az idézőjeles módosításokban különbözik az eredeti cikkben lévőtől, ezért az MKLC-s/számbillentyűs korlátozások rá nem vonatkoznak.
