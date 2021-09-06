
# Vefforritun 1, 2021: Verkefni 3, CSS #1

[Kynning í fyrirlestri](https://youtu.be/_q1B4EHQzgQ).

Verkefnið er framhald af [verkefni 2](https://github.com/vefforritun/vef1-2021-v2), nýtir það efni sem uppsett er í því, og fylgir þeirri verkefnalýsingu. Leyfilegt er að nota [sýnilausn að verkefni 2](https://github.com/vefforritun/vef1-2021-v2-synilausn) (sem gefin er út föstudaginn 10. september).

Nú skal bæta við einföldu útliti á efnið með CSS. Allt útlitið skal vera í `./styles.css` og **allar** HTML skrár skulu vísa í það.

## Útlit

Fyrirmynd að útliti er í `fyrirmynd/` möppu. Öll skjáskot eru tekin í `1000px` breiðum Firefox vafra. Vídeó er tekið í `1000x600` Firefox vafra.

Gera má ráð fyrir að það verði að bæta við auka elementum við lausn/sýnilausn til að geta náð fram útliti.

Þar sem allt útlit skal útfæra í einni CSS skrá, skal huga að cascade og erfðum, þó er fullkomlega eðlilegt að endurtaka eigindi, en t.d. fyrir málsgreinar (`<p>`) þarf aðeins að taka fram einu sinni hvert margin þeirra er.

### Almennt

Setja skal upp „reset“ þ.a. allt `margin` og `padding` frá vafra sé sett í `0`.

Allar málsgreinar skulu hafa eitt bil fyrir neðan sig.

CSS skal vera án villna og **viðvarana** þegar keyrt í gegnum [CSS validator](https://jigsaw.w3.org/css-validator/).

Allar síður skulu vera villulausar ef prófaðar með HTML validator.

Allar síður skulu vera án aðgengisvillna ef prófaðar með aXe, setjið upp viðbót í vafra.

### Haus og valmynd

Fyrirsögn og valmynd skulu vera föst í haus (sjá myndband) með hvítum bakgrunn og taka alla mögulega breidd.

Efni skal taka helming af breidd og vera miðjað, texti (og valmynd) skal vera miðjaður þar innan.

Passa þarf upp á að haus og valmynd fari ekki yfir efni, ekki þarf að finna nákvæma stærð, aðeins að það gildi í `1000px+` breiðum glugga.

### Forsíða

Mynd og texti skulu taka um tvo þriðju af plássi, myndband skal vera hægra megin við og taka um þriðjung af plássi.

### Sækja um nám

Allir hópar af gögnum skulu sitja hlið-við-hlið og taka um fjórðung af plássi.

Fyrir neðan þá skal „Senda umsókn“ takki vera.

Allir reitir skulu hafa eitt bil fyrir neðan sig. Þar sem nánari upplýsingar um reit eru skal það vera fyrir neðan reitinn.

### Áfangar

Hver tafla skal taka helming af plássi, þ.a. tvær séu hlið-við-hlið. Bil skal vera milli raða af töflum.

Setja skal upp border á hvern reit í töflu.

Efni skal hafa fjórðung af bili innan hvers reit.

### Spurt og svarað

Draga skal efni inn um eitt bil frá vinstri.

Milli spurninga skal vera bil, border og annað bil.

### Gildi

* Leturstærð skal vera í grunninn (á `body`) `16px` (eitt bil, ein eining)
* Aðrar stærðir í fyrirmynd eru fjórðungur, hálft, heilt, eða tvöfalt margfeldi af grunnleturstærð
* Aðeins skal nota `px` í grunnleturstærð og breidd á `border`, annars skal nota hlutfallslegar einingar (`em`, `rem`, eða `%`)
* Border er alltaf `1px solid #000`

Til að losna við merki á `<ul>` lista þarf að setja `list-style: none;`.

Til að losna við bil í töflu þarf að setja `border-spacing: 0;`.

### Takmarkanir

Aðeins skal nota eftirfarandi eigindi, og ef tekið fram, viðeigandi gildi:

* `background-color: #fff;`
* `border` og nánari skilgreiningar
* `border-spacing: 0;`
* `box-sizing`
* `clear`
* `display: block;`, `display: inline;`,  og `display: inline-block;`
* `content: '';` (hægt er að nota `:after` til að útbúa block sem „hreinsar“ `float`)
* `float` (notum þetta til að setja blockir hlið-við-hlið, en bara í þetta skipti!)
* `font-size: 16px;`
* `top`, `right`, `bottom`, og `left`
* `list-style: none;`
* `margin` og nánari skilgreiningar
* `padding` og nánari skilgreiningar
* `width`, `min-width`, og `max-width`
* `position: fixed;`
* `text-align: center;`

Ekki þarf að huga að skalanleika (síðan þarf ekki að líta vel út í undir `1000px` skjá).

## Heimasvæði

Setja skal síður upp á [heimasvæði ykkar hjá HÍ](https://uts.hi.is/node/155) undir möppu `.public_html/vefforritun/verkefni3` svo verkefnið verði aðgengilegt á `https://notendur.hi.is/<notendanafn>/vefforritun/verkefni3` þar sem `<notendnafn>` er notendanafnið þitt (t.d. `osk`).

## Mat

* 20% – Snyrtilega uppsett og gilt CSS
* 20% – Aðeins leyfileg eigindi og gildi notuð
* 60% – Útlit skv. fyrirmynd

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 6. september 2021.

## Skil

Skila skal í Canvas í seinasta lagi fyrir lok dags þriðjudaginn 14. september 2021.

Skilaboð skulu innihalda:

* slóð á verkefni
* zip skjali með lausn

Hver dagur eftir skil dregur verkefni niður um 10%, allt að 20% ef skilað fimmtudaginn 16. september 2021 en þá lokar fyrir skil.

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
