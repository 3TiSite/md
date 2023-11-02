<h1 style="justify-content:space-between">3Ti.Site ⋅ Tänker gränslöst<img src="//i-01.eu.org/3Ti/logo.svg" style="user-select:none;margin-top:-1px;width:42px"></h1>

3Ti.Site, Markdown-översättning + flerspråkig statisk webbplatsgenerator.

Bygg snabbt internationella dokument och bloggar som stöder [hundratals språk](https://github.com/i18n-site/node/blob/main/lang/src/index.js) ...

<pre class="langli" style="display:flex;flex-wrap:wrap;background:transparent;border:1px solid #eee;font-size:12px;box-shadow:0 0 3px inset #eee;padding:12px 5px 4px 12px;justify-content:space-between;"><style>pre.langli i{font-weight:300;font-family:s;margin-right:7px;margin-bottom:8px;font-style:normal;color:#666;border-bottom:1px dashed #ccc;}</style><i>English</i><i> 简体中文 </i><i>español</i><i>français</i><i>Deutsch</i><i> 日本語 </i><i>italiano</i><i>한국어</i><i>русский</i><i>português</i><i>shqip</i><i>‫العربية‬</i><i>አማርኛ</i><i>অসমীয়া</i><i>azərbaycan</i><i>Eʋegbe</i><i>Aymar aru</i><i>Gaeilge</i><i>eesti</i><i>ଓଡ଼ିଆ</i><i>Oromoo</i><i>euskara</i><i>беларуская</i><i>bamanakan</i><i>български</i><i>íslenska</i><i>polski</i><i>bosanski</i><i>‫فارسی‬</i><i>भोजपुरी</i><i>Afrikaans</i><i>татар</i><i>dansk</i><i>‫ދިވެހިބަސް‬</i><i>ትግርኛ</i><i>डोगरी</i><i>संस्कृत भाषा</i><i>Filipino</i><i>suomi</i><i>Frysk</i><i>ខ្មែរ</i><i>ქართული</i><i>गोंयची कोंकणी</i><i>ગુજરાતી</i><i>avañe’ẽ</i><i>қазақ тілі</i><i>Kreyòl ayisyen</i><i>Hausa</i><i>Nederlands</i><i>кыргызча</i><i>galego</i><i>català</i><i>čeština</i><i>ಕನ್ನಡ</i><i>corsu</i><i>hrvatski</i><i>Runasimi</i><i>kurdî</i><i>‫کوردیی ناوەندی‬</i><i>Latina</i><i>latviešu</i><i>ລາວ</i><i>lietuvių</i><i>lingála</i><i>Luganda</i><i>Lëtzebuergesch</i><i>Kinyarwanda</i><i>română</i><i>Malagasy</i><i>Malti</i><i>मराठी</i><i>മലയാളം</i><i>Melayu</i><i>македонски</i><i>मैथिली</i><i>Māori</i><i>মৈতৈলোন্</i><i>монгол</i><i>বাংলা</i><i>Mizo ṭawng</i><i>မြန်မာ</i><i>𞄀𞄄𞄰𞄩𞄍𞄜𞄰</i><i>IsiXhosa</i><i>isiZulu</i><i>नेपाली</i><i>norsk</i><i>ਪੰਜਾਬੀ</i><i>‫پښتو‬</i><i>Nyanja</i><i>Akan</i><i>svenska</i><i>Gagana fa'a Sāmoa</i><i>српски</i><i>Sesotho sa Leboa</i><i>Sesotho</i><i>සිංහල</i><i>esperanto</i><i>slovenčina</i><i>slovenščina</i><i>Kiswahili</i><i>Gàidhlig</i><i>Cebuano</i><i>Soomaali</i><i>тоҷикӣ</i><i>తెలుగు</i><i>தமிழ்</i><i>ไทย</i><i>Türkçe</i><i>türkmen dili</i><i>Cymraeg</i><i>‫ئۇيغۇرچە‬</i><i>‫اردو‬</i><i>українська</i><i>o‘zbek</i><i>‫עברית‬</i><i>Ελληνικά</i><i>ʻŌlelo Hawaiʻi</i><i>‫سنڌي‬</i><i>magyar</i><i>chiShona</i><i>հայերեն</i><i>Igbo</i><i>Pagsasao Ilokano</i><i>‫ייִדיש‬</i><i>हिन्दी</i><i>Basa Sunda</i><i>Indonesia</i><i>Jawa</i><i>Èdè Yorùbá</i><i>Tiếng Việt</i><i> 正體中文 </i><i>Xitsonga</i></pre>

Vissa kanske frågar, eftersom alla webbläsare har översättningsfunktioner, är det onödigt att internationalisera webbplatsen?

Jag skulle vilja säga att **endast webbplatser som genererar statiska översättningar kan stödja flerspråkig fulltextsökning på webbplatsen och sökmotoroptimering .**

## Introduktion

Science fiction-romanen &quot;Three Body&quot; (kinesiskt uttal: `3Tǐ` ) fiktionaliserar en främmande civilisation som använder elektromagnetiska vågor för att kommunicera, med transparent tänkande och välmående teknologi.

Bibeln · Första Moseboken :

> På den tiden hade människor över hela världen samma accent och språk.
>
> Bygg ett torn som når himlen, nå Guds port, samla människors hjärtan och sprid ditt rykte.
>
> Herren sa: Människor av samma kultur och ras bildar en egen klan. Att bygga ett torn idag är bara ett förspel, men vi kommer att göra allt i framtiden.
>
> Sedan kom han och skingrade folket på olika ställen, oförmögna att förstå varandra.
>
> Sedan dess har tvister fortsatt, och det finns inget Babeltorn i världen.

Jag hoppas kunna skapa verktyg så att jordens människor kan vara som trekroppsmänniskor, kommunicera utan att vara bundna av språket, och hela mänskligheten kan förenas igen.

Så det fanns [`3Ti.Site`](//3Ti.Site) .

## Markdown-Översättning

Markdown-översättning kan användas självständigt eller med en flerspråkig statisk webbplatsgenerator för att snabbt bygga en webbplats.

Bevara Markdown-formatering, fetstil, listor, titlar, citat, länkar, illustrationer och mer.

Om det finns exempelkod i Markdown kommer provkoden inte att översättas.

## Översättning API Prissättning

0,2 USD för varje 10 000 tecken och en gratis kvot på 100 000 tecken per månad.

## Flerspråkig Webbplatsbyggare

## Handledning

## Funktionsintroduktion

### Behåll Markdown-Format

### Ändra Översättning

Efter att ha modifierat översättningen måste du köra `./i18n.sh` igen för att uppdatera cachen.

### Översättningsanteckningar

Översättningskommentarer måste ange språket efter \```, till exempel ` ```rust` .

Stöder för närvarande kommentarsöversättning för rust, c, cpp, java, js, kaffe, python och bash.

Redigera [tran_md/src/comment.coffee](https://github.com/i18n-site/node/blob/main/tran_md/src/comment.coffee) för att lägga till översättningsstöd för kommentarer på fler språk.

### Konfigurera Proxy

Genom att ställa in följande miljövariabler kan Google Translate API-anrop gå via proxyn.

```bash
export https_proxy=http://127.0.0.1:7890
```

### Variabel Inbäddning

```
测试变量${0}嵌入
```

Variabelnamnet kan vara på engelska, siffror, `-` eller `_` , och variabelnamnet kommer inte att översättas.

### Töm Cachen

```bash
rm -rf .i18n/.cache
```
