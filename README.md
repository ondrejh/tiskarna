# 3D Tiskárna

Jak jsem stavel 3d tiskarnu

## Příběh

Rozhodl jsem se postavit (si) 3D tiskárnu. Je toho plný internet a nemůže to být přeci těžké. Jsem programátor, pracuji s krokovými motory a kolegové mají profi tiskárnu, kterou používají denně. Co víc si přát ...

## Výběr modelu (loop)

Tady už jde do tuhého (to brzo). Internet je sice "plný" různých návodů, schématů a sestav, ale má to háček. Vývoj v segmentu je jaksi překotný, návody nedatované a neúplné, a ty lepší obvykle patří k nějakému prodávanému kitu. Né že bych o koupi nějakého neuvažoval, jen mi to přijde moc snadné.

Po prvním průzkumu se mi zdála jako ideální cesta tiskárna typu [reprap mendel](http://reprap.org/wiki/Mendel). Není nad první dojmy ...

Na druhý pohled se mi zdá lepší [reprap huxley](http://reprap.org/wiki/Huxley). Sice je menší, ale víc se toho bude dát vytisknout v práci. Ale ... ale je osazená motory Nema14 - ty já "Nema"ám.

Pro neznalého začátečníka to skutečně není lehká volba. Zkusím tedy štěstí a dám první slušný návod na typ Mendel. Asi [reprappro.com/documentation/mendel-tricolour](https://reprappro.com/documentation/mendel-tricolour/). Na stránkách prodávali i kit, ale ten už k sehnání není. Proč asi? Nevím. Ale zkusím to.

## Rozpočet
* Závitové tyče, matky, podložky .. 196Kč
* Ložiska 608ZZ .. 36Kč
* Matky, podložky (druhé kolo) .. 132Kč (95Kč jsou těsnící podložky - ty tam nepatří)
* MDF desky .. 1034 Kč (mám toho přibližně 100x víc než potřebuju)

* Ložiska 623ZZ 30ks (Aliexpress) .. 3.00$
* Ložiska LM8UU 24ks (Aliexpress) .. 12.00$
* Řemínek GT2 6mm 10m (Aliexpress) .. 7.99$
* Řemenička GT2 16zubů 5ks (Aliexpress) .. 3.30$
* Heatbed MK2B 1ks (Aliexpress) .. 8.37$
* Řídící deska Melzi 2.0 1ks (DealExtreme) .. 26.11$

* Celkem (zatím) .. 1398 Kč, 55.77$ (1264 Kč)

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

Zdá se, že hlazenky mi zajistí Brašule. Dokonce na míru. A ložiska asi taky (update - ložiska ne, takový nemají - jako u nás). Nechápe, proč jsem to neřekl hned. Závitoviny mají taky kupu. Hold, líná huba holý neštěstí :smile:

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

Jo, abych nezapomněl. Ty hlazenky. Takhle já to s ním mám. Když chci něco po dvou kusech, dodá toho dvě sady. Asi se mu s jednou nechtělo dělat. Díky Brašule :smile:

![smooth rods - two sets](/img/smooth_rods.jpg)

### Sobota 24.6.
Ráno jsem dokoupil potřebný spojovací materiál. Sehnal jsem dokonce i MDF desky - měl jsem obavu, že je ani nebudou mít. Ale o tom později.

Teď mám hotový a seřízený rám. V tomto bodě je návod trochu nejednoznačný a přeházený, ale v principu to funguje. Nevím jestli jsem měl takové štěstí, nebo jestli jsem tak dobře měřil, ale všechno sedí. Osa Y je vodorovná a souosá (test se sklem) a osa Z je kolmá, souosá a seřízená na střed osy Y (je to hlavně práce s úhelnicí). Chce to od začátku stavět na klalitní vodorovné podložce - třeba silna kuchyňská deska je OK.

![Y axis adjustment](/img/frame_adjust.jpg)

Dodávám ještě přehled použitého nářadí: Sklo, nebo jiná plochá tuhá věc na kontrolu osy Y. Kvalitní úhelnice. Laťky - těmi jsem vytvořil spojnici mezi hlazenkami osy Z, abych ji ustavil na střed osy Y - v návodu se používa provázek, nebo gumička - to se mi moc nezdálo. Z jiného kusu stené laťky jsem si vyrobil takové měrky "templaty". V kitu by měl být přiložený takový vypálený hřebínek, ale já ho samozřejmě nemám. Možná si ho taky nechám vypálit - pro zajímavost. Nějaký metr. Fixa - ta se pořád válí na stole. No a 13ka klíč - asi na ďoubání v nose, nééé :smile:

![Frame tools](/img/frame_tools.jpg)

Zpátky k těm MDFkám. Mají je v Trutnově v [DřevoTrust](http://www.drevotrust.cz/cz/). Ochotně je i nařežou, což je potřeba, protože prodávají jen po celých deskách. Cca 2x3m. No, vzhledem k tomu, že budu potřebovat tak A4 (odhad), tak mi asi něco zbyde. Alespoň se mi nestane to co s matkami.

![MDF shopping](/img/shoping_for_mdf.jpg)

Teď začne skutečné shánění. CNC laser, miniaturní a lineární ložiska, řemínek a řemeničky (GT2) aj. Počítám, že už to tak hladce nepůjde. Ale o to ani nešlo ...

### Pondělí 26.6.
Dnes jsem se domluvil se švárou, že mi vypálí díly z MDF desek. Maximální formát, který se vejde do jeho laseru je A3plus. Třetinu desek jsem tedy podle toho připravil.

![MDF formating](/img/mdf_formating.jpg)
![MDF_a3plus](/img/mdf_a3plus.jpg)

Teď mám tedy po 12ti kusech polotovaru od každé tlouštky a ještě dvě třetiny materiálu na půdě.

Ještě musím připravit podklady. V originálech na githubu se bohužel počítá s větší plochou laseru.

### Středa 28.6.
Dnes jsem připravil podklady pro laserování. Zítra ráno jdeme na to.

### Čtvrtek 29.6.
Díly jsou vypálené. Nešlo to zas tak hladce, ale dobrá zpráva je, že to jde i z DXF a propálí to i tu 6mm desku (ale na dvakrát). Cesta je ale prošlápnutá - příště to půjde snáz. Díky [šváro](http://www.razitkanachod.cz/)!

![Lasercut parts](/img/lasercut_parts.jpg)

Do tisku jdou díly na osu Y.

### Pátek 30.6.
Díly jsou vytisknuté, ale ty složitější nejsou ještě vylouhované. No nevadí, stejně nemám ložiska ani řemínek.

![Printed parts Y axis - some of them](/img/printed_miniparts_y_axis.jpg)

### Sobota 1.7.
Nějak jsem to nevydržel a sestavil jsem si alespoň držák motoru. I když bez mikro-ložisek a bez řemeničky.

![Y motor mount parts (no bearings)](/img/y_motor_mount_parts.jpg)
![Y motor mount assembled (no bearings and puley)](/img/y_motor_mount_assembled_nearly.jpg)

### Pondělí 3.7.
Dostal jsem "důkladně" vylouhované zbylé tištěné díly osy Y. Zatím ale stále nemám ložiska.

![Printed parts Y axis - the rest of them](/img/printed_parts_y_therest.jpg)

### Úterý 4.7.
Alespoň nasladko to sestavím...

![Frog parts - no bearings](/img/yaxis_parts_nobearings.jpg)

Taková drobnost: Montážní díry d5mm s osazením pro matku v držáku "žáby" jsou zarostlé tenkou šlupkou a musejí se odvrtat. Kluci v práci tvrdí, že to je chyba v ".STL". Odvrtat to jde snadno a strukturu to nenaruší.
![Frog holder drilling](/img/frog_holder_drilling.jpg)

Druhá poznámka: Jsou předepsané šrouby M3x25mm s imbusovou hlavou. Těch 25mm to je HOODNĚ velká rezerva. Řekl bych že 20mm by bohatě stačilo. Navíc né v každém železářství mají pojistné matky M3 - to jsou opravdu blechy - takže zatím dávám normální (mám jich kupu).
![Frog - long screws](/img/frog_long_screws.jpg)

No ... zatím asi takhle:
![Y axis no bearings](/img/yaxis_no_bearings.jpg)

Sice jsou ložiska a řemínky už nějaký týden na cestě z Číny, ale asi si je objednám někde u nás. Prostě se mi nechce čekat.

### Čtvrtek 13.7.
Ložiska, řemínky, řemeničky, řídící deska a dokonce i headbed jsou stále na cestě. Nechal jsem si zatím vytisknout díly na osu X a nakrátit hlazenky. Bohužel došel obyč materiál, takže jsou z nerezi. Jsem zvědav co na to budou říkat ložiska. Nevím jak se mi mohlo stát, že jsem na tyhle tyčky posledně zapomněl.
![X axis printed parts and rods](/img/x_axis_printed_parts_and_rods.jpg)

### Úterý 18.7.
Přišly díly z Číny. Ložiska LM8UU, ložiska 623, řemínek, řemeničky a řídící deska.
![Parts from China](/img/china_parts.jpg)

### Středa 19.7.
Nemám moc čas, tak alespoň na večer (v noci) skládám osu Y - doplňuju o ložiska a řemen. Mám trochu pocit, že jsem ho přepnul. Uvidíme až se to bude mět hýbat. Řemínku jsem koupil 10m, ale přesto jsem ho chtěl šetřit - bude se hodit. Takže jsem musel podle návodu po připevnění první svorky protahovat celou délku všemi průvlaky na tiskárně. Připadal jsem si, jako když se snažím namotat sežvýkanou videokazetu (pro pamětníky).
![Y axis belt and bearings](/img/y_axis_belt.jpg)

Ale jezdí to pěkně. Tím je hotová [osa Y](https://reprappro.com/documentation/mendel-tricolour/y-axis-assembly/) - tedy kromě koncáku. Už se těším až to zkusím rozhýbat. Škoda, že nemám víc času. Jo, mimochodem. Dnes přišel ještě jeden balík - heatbed - no ten si ještě počká.

![Heatbed package](/img/heatbed.jpg)

### Pondělí 24.7.
Poskládal jsem osu X. Chybí mi jen koncák - stejně jako u osy Y - a budu mít hotový [další krok](https://reprappro.com/documentation/mendel-tricolour/x-axis-assembly/).

![X axis assembled](/img/x_axis_assembled.jpg)

Ty koncáky určitě seženu. Horší ale bude sehnat futýrka na osu Z. Vážně nevím, kde to koupit. Asi zkusím přemluvit bráchu, aby mě je vystrouhnul z mosazi.

### Neděle 13.8.
Před dovolenou mi kluci vytiskli spony na osu Z, sehnal jsem nějaké pružinky a šrouby co jsem ještě neměl a dokonce jsem přez dealera Igusu v práci sehnal i ty futýrka (doplnit typ). Abych se nenudil. Teď mám po dovolené a ani sem na to nesáhnul ... klasika. Snad večer.

pokračování příště ...
