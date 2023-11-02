<h1 style="justify-content:space-between">3Ti.Site ⋅ Tenker uten grenser<img src="//i-01.eu.org/3Ti/logo.svg" style="user-select:none;margin-top:-1px;width:42px"></h1>

3Ti.Site, Markdown-oversettelse + flerspråklig statisk nettstedgenerator.

Bygg raskt internasjonale dokumenter og blogger som støtter [hundrevis av språk](https://github.com/i18n-site/node/blob/main/lang/src/index.js) ...

<pre class="langli" style="display:flex;flex-wrap:wrap;background:transparent;border:1px solid #eee;font-size:12px;box-shadow:0 0 3px inset #eee;padding:12px 5px 4px 12px;justify-content:space-between;"><style>pre.langli i{font-weight:300;font-family:s;margin-right:7px;margin-bottom:8px;font-style:normal;color:#666;border-bottom:1px dashed #ccc;}</style><i>English</i><i> 简体中文 </i><i>español</i><i>français</i><i>Deutsch</i><i> 日本語 </i><i>italiano</i><i>한국어</i><i>русский</i><i>português</i><i>shqip</i><i>‫العربية‬</i><i>አማርኛ</i><i>অসমীয়া</i><i>azərbaycan</i><i>Eʋegbe</i><i>Aymar aru</i><i>Gaeilge</i><i>eesti</i><i>ଓଡ଼ିଆ</i><i>Oromoo</i><i>euskara</i><i>беларуская</i><i>bamanakan</i><i>български</i><i>íslenska</i><i>polski</i><i>bosanski</i><i>‫فارسی‬</i><i>भोजपुरी</i><i>Afrikaans</i><i>татар</i><i>dansk</i><i>‫ދިވެހިބަސް‬</i><i>ትግርኛ</i><i>डोगरी</i><i>संस्कृत भाषा</i><i>Filipino</i><i>suomi</i><i>Frysk</i><i>ខ្មែរ</i><i>ქართული</i><i>गोंयची कोंकणी</i><i>ગુજરાતી</i><i>avañe’ẽ</i><i>қазақ тілі</i><i>Kreyòl ayisyen</i><i>Hausa</i><i>Nederlands</i><i>кыргызча</i><i>galego</i><i>català</i><i>čeština</i><i>ಕನ್ನಡ</i><i>corsu</i><i>hrvatski</i><i>Runasimi</i><i>kurdî</i><i>‫کوردیی ناوەندی‬</i><i>Latina</i><i>latviešu</i><i>ລາວ</i><i>lietuvių</i><i>lingála</i><i>Luganda</i><i>Lëtzebuergesch</i><i>Kinyarwanda</i><i>română</i><i>Malagasy</i><i>Malti</i><i>मराठी</i><i>മലയാളം</i><i>Melayu</i><i>македонски</i><i>मैथिली</i><i>Māori</i><i>মৈতৈলোন্</i><i>монгол</i><i>বাংলা</i><i>Mizo ṭawng</i><i>မြန်မာ</i><i>𞄀𞄄𞄰𞄩𞄍𞄜𞄰</i><i>IsiXhosa</i><i>isiZulu</i><i>नेपाली</i><i>norsk</i><i>ਪੰਜਾਬੀ</i><i>‫پښتو‬</i><i>Nyanja</i><i>Akan</i><i>svenska</i><i>Gagana fa'a Sāmoa</i><i>српски</i><i>Sesotho sa Leboa</i><i>Sesotho</i><i>සිංහල</i><i>esperanto</i><i>slovenčina</i><i>slovenščina</i><i>Kiswahili</i><i>Gàidhlig</i><i>Cebuano</i><i>Soomaali</i><i>тоҷикӣ</i><i>తెలుగు</i><i>தமிழ்</i><i>ไทย</i><i>Türkçe</i><i>türkmen dili</i><i>Cymraeg</i><i>‫ئۇيغۇرچە‬</i><i>‫اردو‬</i><i>українська</i><i>o‘zbek</i><i>‫עברית‬</i><i>Ελληνικά</i><i>ʻŌlelo Hawaiʻi</i><i>‫سنڌي‬</i><i>magyar</i><i>chiShona</i><i>հայերեն</i><i>Igbo</i><i>Pagsasao Ilokano</i><i>‫ייִדיש‬</i><i>हिन्दी</i><i>Basa Sunda</i><i>Indonesia</i><i>Jawa</i><i>Èdè Yorùbá</i><i>Tiếng Việt</i><i> 正體中文 </i><i>Xitsonga</i></pre>

Noen vil kanskje spørre, siden alle nettlesere har oversettelsesfunksjoner, er det unødvendig å internasjonalisere nettstedet?

Jeg vil gjerne si at **bare nettsteder som genererer statiske oversettelser kan støtte flerspråklig fulltekstsøk på stedet og søkemotoroptimalisering .**

## Introduksjon

Science fiction-romanen &quot;Three Body&quot; (kinesisk uttale: `3Tǐ` ) fiksjonaliserer en fremmed sivilisasjon som bruker elektromagnetiske bølger for å kommunisere, med transparent tenkning og velstående teknologi.

Bibel · 1. Mosebok :

> På den tiden hadde folk over hele verden samme aksent og språk.
>
> Bygg et tårn som når himmelen, nå Guds port, samle folks hjerter og spre ditt rykte.
>
> Herren sa: Folk med samme kultur og rase danner en egen klan. Å bygge et tårn i dag er bare et forspill, men vi skal gjøre alt i fremtiden.
>
> Så kom han og spredte folket på forskjellige steder, ute av stand til å forstå hverandre.
>
> Siden den gang har uenighetene fortsatt, og det finnes ikke noe Babeltårn i verden.

Jeg håper å skape verktøy slik at jordens mennesker kan være som trekroppsmennesker, kommunisere uten å være bundet av språk, og hele menneskeheten kan forenes igjen.

Så det var [`3Ti.Site`](//3Ti.Site) .

## Markdown-Oversettelse

Markdown-oversettelse kan brukes uavhengig eller med en flerspråklig statisk nettstedsgenerator for raskt å bygge et nettsted.

Bevar perfekt Markdown-formatering, fet skrift, lister, titler, sitater, lenker, illustrasjoner og mer.

Hvis det er prøvekode i Markdown, vil prøvekoden ikke bli oversatt.

## Oversettelse API-Priser

0,2 USD for hver 10 000 tegn, og en gratis kvote på 100 000 tegn per måned.

## Flerspråklig Nettstedbygger

## Opplæringen

## Funksjon Introduksjon

### Behold Markdown-Format

### Endre Oversettelse

Etter å ha modifisert oversettelsen, må du kjøre `./i18n.sh` på nytt for å oppdatere cachen.

### Oversettelsesnotater

Oversettelseskommentarer må angi språket etter \```, for eksempel ` ```rust` .

Støtter for øyeblikket kommentaroversettelse for rust, c, cpp, java, js, kaffe, python og bash.

Rediger [tran_md/src/comment.coffee](https://github.com/i18n-site/node/blob/main/tran_md/src/comment.coffee) for å legge til oversettelsesstøtte for kommentarer på flere språk.

### Konfigurer Proxy

Ved å angi følgende miljøvariabler kan Google Translate API-kall gå gjennom proxyen.

```bash
export https_proxy=http://127.0.0.1:7890
```

### Variabel Innebygging

```
测试变量${0}嵌入
```

Variabelnavnet kan være på engelsk, tall, `-` eller `_` , og variabelnavnet vil ikke bli oversatt.

### Tømme Hurtigbufferen

```bash
rm -rf .i18n/.cache
```
