<h1 style="justify-content:space-between">3Ti.Site ⋅ Thinking Borderless <img src="//i-01.eu.org/3Ti/logo.svg" style="user-select:none;margin-top:-1px;width:42px"></h1>

3Ti.Site, Markdown prevod + višejezični generator statičkog sajta.

Brzo napravite međunarodne dokumente i blogove koji podržavaju [stotine jezika](https://github.com/i18n-site/node/blob/main/lang/src/index.js) ...

<pre class="langli" style="display:flex;flex-wrap:wrap;background:transparent;border:1px solid #eee;font-size:12px;box-shadow:0 0 3px inset #eee;padding:12px 5px 4px 12px;justify-content:space-between;"><style>pre.langli i{font-weight:300;font-family:s;margin-right:7px;margin-bottom:8px;font-style:normal;color:#666;border-bottom:1px dashed #ccc;}</style><i>English</i><i> 简体中文 </i><i>español</i><i>français</i><i>Deutsch</i><i> 日本語 </i><i>italiano</i><i>한국어</i><i>русский</i><i>português</i><i>shqip</i><i>‫العربية‬</i><i>አማርኛ</i><i>অসমীয়া</i><i>azərbaycan</i><i>Eʋegbe</i><i>Aymar aru</i><i>Gaeilge</i><i>eesti</i><i>ଓଡ଼ିଆ</i><i>Oromoo</i><i>euskara</i><i>беларуская</i><i>bamanakan</i><i>български</i><i>íslenska</i><i>polski</i><i>bosanski</i><i>‫فارسی‬</i><i>भोजपुरी</i><i>Afrikaans</i><i>татар</i><i>dansk</i><i>‫ދިވެހިބަސް‬</i><i>ትግርኛ</i><i>डोगरी</i><i>संस्कृत भाषा</i><i>Filipino</i><i>suomi</i><i>Frysk</i><i>ខ្មែរ</i><i>ქართული</i><i>गोंयची कोंकणी</i><i>ગુજરાતી</i><i>avañe’ẽ</i><i>қазақ тілі</i><i>Kreyòl ayisyen</i><i>Hausa</i><i>Nederlands</i><i>кыргызча</i><i>galego</i><i>català</i><i>čeština</i><i>ಕನ್ನಡ</i><i>corsu</i><i>hrvatski</i><i>Runasimi</i><i>kurdî</i><i>‫کوردیی ناوەندی‬</i><i>Latina</i><i>latviešu</i><i>ລາວ</i><i>lietuvių</i><i>lingála</i><i>Luganda</i><i>Lëtzebuergesch</i><i>Kinyarwanda</i><i>română</i><i>Malagasy</i><i>Malti</i><i>मराठी</i><i>മലയാളം</i><i>Melayu</i><i>македонски</i><i>मैथिली</i><i>Māori</i><i>মৈতৈলোন্</i><i>монгол</i><i>বাংলা</i><i>Mizo ṭawng</i><i>မြန်မာ</i><i>𞄀𞄄𞄰𞄩𞄍𞄜𞄰</i><i>IsiXhosa</i><i>isiZulu</i><i>नेपाली</i><i>norsk</i><i>ਪੰਜਾਬੀ</i><i>‫پښتو‬</i><i>Nyanja</i><i>Akan</i><i>svenska</i><i>Gagana fa'a Sāmoa</i><i>српски</i><i>Sesotho sa Leboa</i><i>Sesotho</i><i>සිංහල</i><i>esperanto</i><i>slovenčina</i><i>slovenščina</i><i>Kiswahili</i><i>Gàidhlig</i><i>Cebuano</i><i>Soomaali</i><i>тоҷикӣ</i><i>తెలుగు</i><i>தமிழ்</i><i>ไทย</i><i>Türkçe</i><i>türkmen dili</i><i>Cymraeg</i><i>‫ئۇيغۇرچە‬</i><i>‫اردو‬</i><i>українська</i><i>o‘zbek</i><i>‫עברית‬</i><i>Ελληνικά</i><i>ʻŌlelo Hawaiʻi</i><i>‫سنڌي‬</i><i>magyar</i><i>chiShona</i><i>հայերեն</i><i>Igbo</i><i>Pagsasao Ilokano</i><i>‫ייִדיש‬</i><i>हिन्दी</i><i>Basa Sunda</i><i>Indonesia</i><i>Jawa</i><i>Èdè Yorùbá</i><i>Tiếng Việt</i><i> 正體中文 </i><i>Xitsonga</i></pre>

Neki ljudi mogu pitati, budući da svi pretraživači imaju funkcije prevođenja, da li je nepotrebno internacionalizirati web stranicu?

Želio bih reći da**samo web stranice koje generiraju statičke prijevode mogu podržati višejezičnu pretragu cijelog teksta na stranici i optimizaciju tražilice** .

## Uvod

Naučnofantastični roman &quot;Tri tijela&quot; (kineski izgovor:`3Tǐ` ) fikcionalizira vanzemaljsku civilizaciju koja koristi elektromagnetne valove za komunikaciju, s transparentnim razmišljanjem i prosperitetnom tehnologijom.

Biblija·Postanak :

> U to vrijeme, ljudi širom svijeta imali su isti naglasak i jezik.
>
> Izgradite kulu koja seže do neba, dođite do Božijih vrata, okupite srca ljudi i širite svoju reputaciju.
>
> Gospod je rekao: Ljudi iste kulture i rase formiraju svoj klan. Izgradnja tornja danas je samo uvod, ali sve ćemo učiniti u budućnosti.
>
> Onda je došao i rasuo narod po raznim mestima, ne razumevajući jedni druge.
>
> Od tada se nastavljaju sporovi, a na svijetu ne postoji vavilonska kula.

Nadam se da ću stvoriti alate tako da ljudi na Zemlji mogu biti kao ljudi sa tri tijela, komunicirati bez da budu vezani jezikom, i cijelo čovječanstvo može ponovo biti ujedinjeno.

Dakle, postojao je [`3Ti.Site`](//3Ti.Site) .

## Markdown Translation

Markdown prijevod se može koristiti samostalno ili sa višejezičnim generatorom statičkih stranica za brzu izradu web stranice.

Savršeno sačuvajte Markdown formatiranje, podebljano, liste, naslove, citate, veze, ilustracije i još mnogo toga.

Ako postoji uzorak koda u Markdownu, uzorak koda neće biti preveden.

## Cijena API-Ja Za Prevođenje

0,2 USD za svakih 10.000 znakova i besplatna kvota od 100.000 znakova mjesečno.

## Multilingual Site Builder

## Tutorial

## Funkcija Uvod

### Zadržite Markdown Format

### Modify Translation

Nakon izmjene prijevoda, morate ponovo pokrenuti `./i18n.sh` da ažurirate keš memoriju.

### Translation Notes

Komentari prijevoda moraju naznačiti jezik nakon \```, kao što je ` ```rust` .

Trenutno podržava prevođenje komentara za rust, c, cpp, java, js, kafu, python i bash.

Uredite [tran_md/src/comment.coffee](https://github.com/i18n-site/node/blob/main/tran_md/src/comment.coffee) da dodate podršku za prevod za komentare na više jezika.

### Konfiguriši Proxy

Postavljanje sljedećih varijabli okruženja omogućava pozivima Google Translate API-ja da prolaze kroz proxy.

```bash
export https_proxy=http://127.0.0.1:7890
```

### Variable Embedding

```
测试变量${0}嵌入
```

Naziv varijable može biti na engleskom, brojevi, `-` ili `_` , a naziv varijable neće biti preveden.

### Ispraznite Keš Memoriju

```bash
rm -rf .i18n/.cache
```
