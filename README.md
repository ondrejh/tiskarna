# 3D Tiskárna

Jak jsem stavel 3d tiskarnu

## Příběh

Rozhodl jsem se postavit (si) 3D tiskárnu. Je toho plný internet a nemůže to být přeci těžké. Jsem programátor, pracuji s krokovými motory a kolegové mají profi tiskárnu, kterou používají denně. Co víc si přát ...

## Výběr modelu (loop)

Tady už jde do tuhého (to brzo). Internet je sice "plný" různých návodů, schématů a sestav, ale má to háček. Vývoj v segmentu je jaksi překotný, návody nedatované a neúplné, a ty lepší obvykle patří k nějakému prodávanému kitu. Né že bych o koupi nějakého neuvažoval, jen mi to přijde moc snadné.

Po prvním průzkumu se mi zdála jako ideální cesta tiskárna typu [reprap mendel](http://reprap.org/wiki/Mendel). Není nad první dojmy ...

Na druhý pohled se mi zdá lepší [reprap huxley](http://reprap.org/wiki/Huxley). Sice je menší, ale víc se toho bude dát vytisknout v práci. Ale ... ale je osazená motory Nema14 - ty já "Nema"ám.

Pro neznalého začátečníka to skutečně není lehká volba. Zkusím tedy štěstí a dám první slušný návod na typ Mendel. Asi [reprappro.com/documentation/mendel-tricolour](https://reprappro.com/documentation/mendel-tricolour/). Na stránkách prodávali i kit, ale ten už k sehnání není. Proč asi? Nevím. Ale zkusím to.

## Build log

### Pondělí 19.6.
Procházím DXko a podobné "číňany", co se dá koupit. Zatím objednávám jen řídící desku - je to trochu předčasné, ale mám strach, že byh jí příště nenašel. Link přidám později (TODO)

### Úterý 20.6.
V železářství kupuju 7 metrových závitových tyčí M8 a matky s vějířovými podložkami - cca 200kč. Hlazenky nemají (zatím). Na ložiska se zeptám v práci - update (21.6.): prý je mají v kšeftu se zahradní technikou.

### Středa 21.6.
Čeká mě první "na zkoušku" vytisknutý díl. Jde o držák motoru osy Z - patří do [konstrukce rámu](https://reprappro.com/documentation/mendel-tricolour/frame-assembly/). Vypadá dobře, nemůžu se dočkat na další.

![z_motor_holder_printed](/img/z_motor_holder_printed.jpg)

Znovu procházím návod a zjišťuju, že závitových tyčí M8 bude potřeba asi jen 6. Ta sedmá je M5 pohonu osy.

### Čtvrtek 22.6.
Čekání na díly ... to může trvat věčnost, než se na tiskárně dostanu na řadu. Zatím jsem alespoň naporcoval závitovinu. Opravil jsem si na to starou stolní úhlovou rozbušovačku. Navařil jsem jí kolečka a madlo, aby se dala líp přemísťovat a vyměnil jí kabel a koncovu na nový 16A pětíkolík. Nakrátil jsem na ní dvě tyčky a zbytek jsem dodělal pilkou na železo a pilníkem. Flexa to prostě moc ubírá, řeže na hrubo, pálí pozink, a ani zabroušení není to pravé, takže se pak musí opravovat závit. Někdy jsou prostě lepší jednoduché nástroje...

![thread rods, nuts and lock washers](/img/thread_rods.jpg)

Zdá se, že hlazenky mi zajistí Brašule. Dokonce na míru. A ložiska asi taky (update - ložiska ne, takový nemají - jako u nás). Nechápe, proč jsem to neřekl hned. Závitoviny mají taky kupu. Hold, líná huba holý neštěstí :-)

### Pátek 23.6.
Tištěné díly framu jsou hotové (asi protekce, nebo co). Ložiska vezmu cestou z práce v tom [kšeftu se sekačkama](www.agrico-sro.cz). Hlazenky budou večer u Brašuleho. Můžu skládat.

![frame printed parts](/img/frame_printed_parts.jpg)

Postup přesně podle [návodu](https://reprappro.com/documentation/mendel-tricolour/frame-assembly/). Při montáži trojůhelníků je potřeba zkontrolovat aby byly nohy proti sobě - to je i v návodu zdůrazněno. Nevšiml jsem si ale, že by tam bylo zdůrazněno, že je na totéž potřeba dát pozor, když se trojůhelníky sesazují na příčníky. Takže jsem to dělal dvakrát.

![triangle assembling](/img/one_triangle.jpg)
![triangles ready](/img/two_triangles.jpg)

Příprava příčníků. V tomhle návodu nic moc. Je tam sice textové schéma "nut,washer,nut ..." ale v tom se dá snadno ztratit. Na [www.reprap.org](http://www.reprap.org/) jsem viděl i pěkné [grafické schéma](http://reprap.org/wiki/File:Rear-rods.png). Ale nakonec i podle tohohle se to dá.

![cross bars](/img/cross_bars.jpg)
![cross bars assembled](/img/cross_bars_assembled.jpg)

Tak, A došly mi matky a podložky. Nějak jsem si špatně prošel návod a špatně jsem to sečetl. Myslel jsem, že budu potřebovat něco málo přez 50ks, tak jsem vzal 60. A jsou pryč a ještě zdaleka nejsem u konce. Ach jo ... Dnes už je nikde nekoupím. Takže pro dnešek konec.

![cant continue .. out of nuts](/img/out_of_nuts.jpg)

pokračování příště ...
