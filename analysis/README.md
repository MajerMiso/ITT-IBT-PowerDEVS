# __Analýza a návrh používateľského rozhrania pre PowerDEVS__
### __Analýza nedostatkov__

- Elementy sa niekedy problematicky spájajú
- Občasný bug po spojení a presunutí elementov - nesprávne umiestnený prepoj medzi elementmi
- Oblasť výberu nie je viditeľne vyznačená
- Chýba možnosť zoskupenia vyznačených elementov do "Coupled" bloku
- Pre zanorenie do "Coupled" elementu nestačí dvojklik
- Chýba tlačítko na pohodlné vynorenie z "Coupled" elementu
- Po potiahnutí na plátno elementy nie sú vycentrované na kurzor stredom, ale ľavým horným rohom
- Zdĺhavé vyhľadávanie elementov, chýbajúca vyhľadávacia lišta
- Množstvo redundantných tlačítok v hornej časti obrazovky, ktoré sa už na lište nachádzajú v submenu File a Edit a ich akcie sú zároveň intuitívne vykonateľné štandardnými klávesovými skratkami (Open, Save, Copy, Paste)
-V Petriho sieťach sa nezobrazuje počet tokenov vo vnútri elementu "Place", prechody nemajú zobrazenú číselnú podmienku na prechod


### __Návrh riešení__
- Lepšie zvýraznenie aktuálne vybranej kategórie na bočnej lište
- Zväčšenie (neviditeľnej) plochy na prepoj elementov
- Zobrazovanie oblasti výberu pre lepšiu prehľadnosť
- Pridanie možnosti zoskupenia vybraných elementov do "Coupled" elementu
- Nahradenie akcie po dvojkliku -> zobrazenie podelementov, alebo zdrojového kódu
- Centrovanie elementov na stred kurzora
- Pridanie vyhľadávacej lišty pre elementy
- V hornej časti obrazovky ponechať len potrebné tlačítka (Simulate, Debug, Logs...). Umiestnenie a dizajn tlačítok podobný ako [SimScale](https://www.simscale.com/press/user-interface-update-cloud/) alebo [Blender](https://www.blender.org/)
- K tlačítkam pridať možnosť vynorenia sa z "Coupled" elementu
- Možnosť tmavej témy
- V Petriho sieťach zobrazovať počet tokenov v elemente "Place". Do určitého počtu zorazovať bodky, ďalej čísla
- Zobrazovanie hodnoty prechodu v Petriho sieťach