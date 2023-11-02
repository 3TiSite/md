<h1 style="justify-content:space-between">3Ti.Site ⋅ Pensando sin fronteras <img src="//i-01.eu.org/3Ti/logo.svg" style="user-select:none;margin-top:-1px;width:42px"></h1>

3Ti.Site, traducción Markdown + generador de sitios estáticos multilingüe.

Cree rápidamente documentos y blogs internacionales que admitan [cientos de idiomas](https://github.com/i18n-site/node/blob/main/lang/src/index.js) ...

<pre class="langli" style="display:flex;flex-wrap:wrap;background:transparent;border:1px solid #eee;font-size:12px;box-shadow:0 0 3px inset #eee;padding:12px 5px 4px 12px;justify-content:space-between;"><style>pre.langli i{font-weight:300;font-family:s;margin-right:7px;margin-bottom:8px;font-style:normal;color:#666;border-bottom:1px dashed #ccc;}</style><i>English</i><i> 简体中文 </i><i>español</i><i>français</i><i>Deutsch</i><i> 日本語 </i><i>italiano</i><i>한국어</i><i>русский</i><i>português</i><i>shqip</i><i>‫العربية‬</i><i>አማርኛ</i><i>অসমীয়া</i><i>azərbaycan</i><i>Eʋegbe</i><i>Aymar aru</i><i>Gaeilge</i><i>eesti</i><i>ଓଡ଼ିଆ</i><i>Oromoo</i><i>euskara</i><i>беларуская</i><i>bamanakan</i><i>български</i><i>íslenska</i><i>polski</i><i>bosanski</i><i>‫فارسی‬</i><i>भोजपुरी</i><i>Afrikaans</i><i>татар</i><i>dansk</i><i>‫ދިވެހިބަސް‬</i><i>ትግርኛ</i><i>डोगरी</i><i>संस्कृत भाषा</i><i>Filipino</i><i>suomi</i><i>Frysk</i><i>ខ្មែរ</i><i>ქართული</i><i>गोंयची कोंकणी</i><i>ગુજરાતી</i><i>avañe’ẽ</i><i>қазақ тілі</i><i>Kreyòl ayisyen</i><i>Hausa</i><i>Nederlands</i><i>кыргызча</i><i>galego</i><i>català</i><i>čeština</i><i>ಕನ್ನಡ</i><i>corsu</i><i>hrvatski</i><i>Runasimi</i><i>kurdî</i><i>‫کوردیی ناوەندی‬</i><i>Latina</i><i>latviešu</i><i>ລາວ</i><i>lietuvių</i><i>lingála</i><i>Luganda</i><i>Lëtzebuergesch</i><i>Kinyarwanda</i><i>română</i><i>Malagasy</i><i>Malti</i><i>मराठी</i><i>മലയാളം</i><i>Melayu</i><i>македонски</i><i>मैथिली</i><i>Māori</i><i>মৈতৈলোন্</i><i>монгол</i><i>বাংলা</i><i>Mizo ṭawng</i><i>မြန်မာ</i><i>𞄀𞄄𞄰𞄩𞄍𞄜𞄰</i><i>IsiXhosa</i><i>isiZulu</i><i>नेपाली</i><i>norsk</i><i>ਪੰਜਾਬੀ</i><i>‫پښتو‬</i><i>Nyanja</i><i>Akan</i><i>svenska</i><i>Gagana fa'a Sāmoa</i><i>српски</i><i>Sesotho sa Leboa</i><i>Sesotho</i><i>සිංහල</i><i>esperanto</i><i>slovenčina</i><i>slovenščina</i><i>Kiswahili</i><i>Gàidhlig</i><i>Cebuano</i><i>Soomaali</i><i>тоҷикӣ</i><i>తెలుగు</i><i>தமிழ்</i><i>ไทย</i><i>Türkçe</i><i>türkmen dili</i><i>Cymraeg</i><i>‫ئۇيغۇرچە‬</i><i>‫اردو‬</i><i>українська</i><i>o‘zbek</i><i>‫עברית‬</i><i>Ελληνικά</i><i>ʻŌlelo Hawaiʻi</i><i>‫سنڌي‬</i><i>magyar</i><i>chiShona</i><i>հայերեն</i><i>Igbo</i><i>Pagsasao Ilokano</i><i>‫ייִדיש‬</i><i>हिन्दी</i><i>Basa Sunda</i><i>Indonesia</i><i>Jawa</i><i>Èdè Yorùbá</i><i>Tiếng Việt</i><i> 正體中文 </i><i>Xitsonga</i></pre>

Algunas personas pueden preguntarse, dado que todos los navegadores tienen funciones de traducción, ¿es innecesario internacionalizar el sitio web?

Me gustaría decir que**solo los sitios web que generan traducciones estáticas pueden admitir la búsqueda de texto completo en el sitio multilingüe y la optimización de motores de búsqueda** .

## Introducción

La novela de ciencia ficción &quot;Three Body&quot; (pronunciación china:`3Tǐ` ) ficcionaliza una civilización extraterrestre que utiliza ondas electromagnéticas para comunicarse, con pensamiento transparente y tecnología próspera.

Biblia·Génesis :

> En aquella época, la gente de todo el mundo tenía el mismo acento y el mismo idioma.
>
> Construye una torre que llegue al cielo, llega a la puerta de Dios, reúne los corazones de las personas y difunde tu reputación.
>
> El Señor dijo: Las personas de la misma cultura y raza forman su propio clan. Construir una torre hoy es sólo un preludio, pero lo haremos todo en el futuro.
>
> Luego vino y dispersó a la gente por distintos lugares, sin poder entenderse unos a otros.
>
> Desde entonces, las disputas han continuado y no existe la Torre de Babel en el mundo.

Espero crear herramientas para que los habitantes de la tierra puedan ser como personas de tres cuerpos, comunicarse sin estar limitados por el lenguaje y toda la humanidad pueda volver a unirse.

Entonces, estaba [`3Ti.Site`](//3Ti.Site) .

## Traductor De Markdown

La traducción de Markdown se puede utilizar de forma independiente o con un generador de sitios estáticos en varios idiomas para crear rápidamente un sitio web.

Conserve perfectamente el formato Markdown, negrita, listas, títulos, citas, enlaces, ilustraciones y más.

Si hay un código de muestra en Markdown, el código de muestra no se traducirá.

## Precios De La API De Traducción

0,2 USD por cada 10.000 caracteres y una cuota gratuita de 100.000 caracteres al mes.

## Creador De Sitios Multilingües

## Tutorial

## Introducción A La Función

### Mantener Formato De Rebajas

### Modificar Traducción

Después de modificar la traducción, debe volver a ejecutar `./i18n.sh` para actualizar el caché.

### Notas De Traducción

Los comentarios de traducción deben indicar el idioma después de \```, como ` ```rust` .

Actualmente admite la traducción de comentarios para Rust, C, CPP, Java, JS, Coffee, Python y Bash.

Edite [tran_md/src/comment.coffee](https://github.com/i18n-site/node/blob/main/tran_md/src/comment.coffee) para agregar soporte de traducción para comentarios en más idiomas.

### Configurar Proxy

La configuración de las siguientes variables de entorno permite que las llamadas a la API de Google Translate pasen por el proxy.

```bash
export https_proxy=http://127.0.0.1:7890
```

### Incrustación De Variables

```
测试变量${0}嵌入
```

El nombre de la variable puede estar en inglés, números, `-` o `_` , y el nombre de la variable no se traducirá.

### Vaciar El Caché

```bash
rm -rf .i18n/.cache
```
