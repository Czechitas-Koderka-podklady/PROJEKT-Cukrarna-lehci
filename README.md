# Cukrárna (lehčí varianta)

Dobrovolný kol pro kurz Staň se kóderkou od Czechitas. Když ho odevzdáš, koučové ti k němu napíšou zpětnou vazbu. Toto je **lehčí*** varianta úkolu, více se dozvíš v sekci Obtížnosti úkolu.

- [Cíl úkolu](#Cíl-úkolu)
- [Grafické zadání](#Grafické-zadání)
- [Obtížnosti úkolu](#Obtížnosti-úkolu)
- [Jak si stáhnout podklady](#Jak-si-stáhnout-podklady)

Než začneš s projektem cokoliv dělat, přečti si prosím celý tento text až do konce.

Za úkol máš nakódovat design podle grafického návrhu. Jedná se o úvodní stránku webu fiktivní cukrárny. Na výsledný vzhled projektu se podívej na obrázku *ukazka-vysledku.jpg*.

Možná při pohledu na obrázek padáš do mdlob a nevěříš, že takovou stránku zvládneš nakódovat. A já ti tvrdím, že zvládneš. Nebude to lehké, ale je to naprosto proveditelné. Potřebné znalosti na to už máš.

![Ukázka výsledku](ukazka-vysledku.jpg)


## Cíl úkolu

Cílem projektu je procvičit si použití různých technik:
- **Flexbox**
  - tento úkol je plný flexboxů
  - pomocí flexboxu udělej horní proužek s logem a menu
  - všechny sekce, kde je obrázek a vedle něj text, udělej také flexboxem. Textovou polovinu a obrázek můžeš pomocí flexboxu navzájem k sobě vertikálně vycentrovat.
  - nabídka dortíků je také flexbox, ale to už ti asi bylo jasné dávno
  - na horní banner s cupcaky flexbox nepotřebuješ - to je jenom sekce s obrázkem na pozadí, kde obsah má velký pravý padding (nebo margin)
- **Margin a padding**
  - v tomto úkolu nepotřebuješ žádné pozicování - vše vyřešíš jen pomocí flexboxu a marginu a paddingu
  - nezapomeň, že například nadpisy a odstavce mají ve výchozím stylu prohlížeče nastavený margin nahoru a dolů. Někdy je potřeba jeden z těchto marginů vynulovat (např. nad nadpisem), aby se ti nesčítal s paddingem prvku, ve kterém nadpis leží, a nad nadpisem tak nebyla větší mezera než chceš.
  - pamatuj na základní poučku:
    - chci-li obsah prvku odsadit od jeho okraje, použiji padding
    - chci-li odsunout dva prvky od sebe navzájem, použiji margin


## Grafické zadání

Všechny potřebné rozměry, použitá písma, barvy, apod. najdeš na obrázku *zadani-ukolu.png*. Spoustu z těchto informací máš připravenou také v komentáři v souboru *style.css*.

![zadání úkolu](zadani-ukolu.png)


## Obtížnosti úkolu

Zadání tohoto projektu je vytvořeno ve dvou úrovních obtížnosti. Tento repozitář obsahuje výchozí **lehčí úroveň obtížnosti**. Doporučuji nejprve zkusit standardní obtížnost.

### Lehčí obtížnost
- obsažená v tomto repozitáři
- grafické zadání je stejné, ale v HTML je kompletně připravený obsah včetně struktury, obalových prvků a přidaných CSS tříd
- v HTML už máš připojená písma z Google Fonts
- v této obtížnosti nemusíš HTML vůbec upravovat - stačí si ho prostudovat, abys věděla jaké prvky/třídy máš stylovat a "jenom" k nim napsat CSS

### Standardní obtížnost
- dostupná v [druhém repozitáři](https://github.com/Czechitas-Koderka-podklady/PROJEKT-Cukrarna)
- v HTML najdeš pouze obsahové elementy (nadpisy, odstavce, obrázky)
- sama si do HTML musíš dopsat další strukturu, která je nutná, abys mohla HTML nastylovat podle grafického zadání
- musíš vymyslet, do jakých prvků obsah zabalíš a jaké třídy jim přidáš
- nezapomeň si připojit správná písma z Google Fonts

Je úplně v pořádku, pokud si nakonec zvolíš jednodušší variantu (např. kvůli nedostatku času), ale doporučuji, abys nejprve zkusila standardní obtížnost, kde si musíš sama vytvořit i HTML strukturu a pojmenovat CSS třídy. Není to zase o tolik těžší a v reálném životě ti také nikdo HTML připravovat nebude. Jako kóderka dostaneš grafický návrh a ten budeš muset převést do HTML a CSS. Budeš-li si u bonusových úkolů volit jednodušší obtížnosti, nakonec zjistíš, že sice umíš CSS, ale dělá ti problém vymyslet a napsat si vlastní HTML.


## Jak si stáhnout podklady

1. Udělej si **fork** této repozitáře - tím se ti úkol zkopíruje do tvého GitHub profilu.
2. Forknutou repozitář si naklonuj k sobě na disk.

Pokud nevíš, co je to **fork repozitáře** a jak ho provést, podívej se na [krátké video](https://youtu.be/K7rE3jRCjD4).

