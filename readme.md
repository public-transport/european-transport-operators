# European transport operators

This is a list of european long-distance transport operators, available API endpoints, GTFS feeds and client modules. The long-term goal would be to have [GTFS](https://developers.google.com/transit/gtfs/) / [FPTF](https://github.com/public-transport/friendly-public-transport-format) for every single operator which would allow us to compose a giant european long-distance transport feed. That would be pretty cool, huh? Let's get to work then… 🔨

- [Train](#train)
- [Coach](#coach)
- [Ferry](#ferry)

## Train

Operator | Countries | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | [`station`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#station) | [`line`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#line) | [`route`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#route) | [`schedule`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#schedule) | [`journey`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#journey)
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------ | ------- | ---------- | ---------
[*Interrail\**](https://www.interrail.eu/) | 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/interrail/) | ❔ | ❔ | ❔ | ❔ | ❔
[DB](https://www.bahn.de) | 🇩🇪 | [✅](http://data.deutschebahn.com/dataset?groups=apis) | ✅ *todo* | ❌ | [✅](https://github.com/derhuerst/db-hafas/) | ❔ | ❔ | ❔ | ❔ | ❔
[SNCF](http://www.sncf.fr) | 🇫🇷 | [✅](https://www.digital.sncf.com/startup/api) | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/sncf) | ❔ | ❔ | ❔ | ❔ | ❔
[CD](https://www.cd.cz/) | 🇨🇿 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[ÖBB](http://www.oebb.at) | 🇦🇹 | ❌ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[SBB](https://www.sbb.ch) | 🇨🇭 | [✅](https://data.sbb.ch/api/v1/documentation) | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[SJ](https://www.sj.se/) | 🇸🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[NSB](https://www.nsb.no/) | 🇳🇴 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[VR](https://www.vr.fi) | 🇫🇮 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[DSB](https://www.dsb.dk/) | 🇩🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[NS](https://www.ns.nl/) | 🇳🇱 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[SNCB](http://www.belgianrail.be/) | 🇧🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[CFL](http://www.cfl.lu/) | 🇱🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[CP](https://www.cp.pt) | 🇵🇹 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[renfe](http://www.renfe.com/) | 🇪🇸 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Trenitalia](http://www.trenitalia.com) | 🇮🇹 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[PKP](http://pkp.pl/) | 🇵🇱 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[HŽPP](http://www.hzpp.hr/) | 🇭🇷 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[CFR](https://www.cfrcalatori.ro/) | 🇷🇴 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[SŽ](http://www.slo-zeleznice.si) | 🇸🇮 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[LDz](https://www.ldz.lv/) | 🇱🇻 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Бч](http://www.rw.by/) | 🇧🇾 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[LG](http://www.litrail.lt) | 🇱🇹 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[GR](http://www.railway.ge) | 🇬🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[JSC](http://serbianrailways.com/) | 🇷🇸 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[ŽSR](http://www.slovakrail.sk/) | 🇸🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[EVR](http://www.evr.ee/) | 🇪🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[MÁV](https://www.mavcsoport.hu/) | 🇭🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Irish Rail](http://www.irishrail.ie) | 🇮🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[УЗ](http://www.uz.gov.ua/en/) | 🇺🇦 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[RZD](http://pass.rzd.ru/main-pass/public/en) | 🇷🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[CFM](http://www.railway.md/) | 🇲🇩 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[BDZ](http://www.bdz.bg) | 🇧🇬 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[TrainOSE](http://www.trainose.gr/) | 🇬🇷 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[TCDD](http://www.tcdd.gov.tr/) | 🇹🇷 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[МЖ](http://www.mzi.mk/) | 🇲🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Trainkos](http://www.trainkos.com/) | 🇽🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[ŽPCG](http://www.zcg-prevoz.me/) | 🇲🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[ŽFBH](http://www.zfbh.ba/) | 🇧🇦 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[ADY](https://ady.az/) | 🇦🇿 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[KTZ](http://www.railways.kz/) | 🇰🇿 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔


\*Not an operator, still interesting though

Missing countries: 🇦🇱 🇦🇲 🇸🇲 🇬🇧 🇻🇦

## Coach

Operator | Countries | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | [`station`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#station) | [`line`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#line) | [`route`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#route) | [`schedule`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#schedule) | [`journey`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#journey)
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------ | ------- | ---------- | ---------
[FlixBus](https://www.flixbus.com/) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/meinfernbus) | ❔ | ❔ | ❔ | ❔ | ❔
[Eurolines (DE)](https://www.eurolines.de) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/eurolines-de) | ❔ | ❔ | ❔ | ❔ | ❔
[PolskiBus](http://www.polskibus.com) | 🇵🇱 🇪🇺 | ❌ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Ouibus](https://www.ouibus.com/) | 🇫🇷 🇪🇺 | [✅](https://api.idbus.com/) | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/ouibus) | ❔ | ❔ | ❔ | ❔ | ❔
[MegaBus](https://uk.megabus.com/) | 🇬🇧 🇪🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Deinbus](https://www.deinbus.de/) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/deinbus) | ❔ | ❔ | ❔ | ❔ | ❔
[Ecolines](https://ecolines.net) | 🇪🇺, East | ❌ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[LuxExpress](https://luxexpress.eu) | 🇪🇺, East | ❌ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Nettbuss](https://www.nettbuss.se/) | 🇸🇪 🇳🇴 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[RegioJet](https://www.regiojet.com/) | 🇨🇿 🇸🇰 🇪🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔

## Ferry

Operator | Countries | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | [`station`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#station) | [`line`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#line) | [`route`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#route) | [`schedule`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#schedule) | [`journey`](https://github.com/public-transport/friendly-public-transport-format/blob/master/docs/readme.md#journey)
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------ | ------- | ---------- | ---------
[Stena Line](https://www.stenaline.de/) | 🇪🇺, North, Baltic | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[DFDS](https://www.dfdsseaways.com/) | 🇪🇺, North, Baltic | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Scandlines](https://www.scandlines.com/) | 🇸🇪 🇩🇰 🇩🇪 | ❌ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Finnlines](https://www.finnlines.com/) | 🇫🇮 🇸🇪 🇩🇪 | ❌ | ✅ *todo* | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[tallink / Silja Line](https://www.tallink.com/) | 🇸🇪 🇫🇮 🇪🇪 🇱🇻 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/tallink) | ❔ | ❔ | ❔ | ❔ | ❔
[Viking Line](http://www.vikingline.fi/) | 🇫🇮 🇪🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Wasa Line](https://www.wasaline.com/) | 🇸🇪 🇫🇮 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[St. Peter Line](https://stpeterline.com/) | 🇸🇪 🇫🇮 🇪🇪 🇷🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Polferries](http://polferries.pl/) | 🇵🇱 🇸🇪 🇩🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Unity Line](https://www.unityline.pl/) | 🇵🇱 🇸🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[TT Line](https://ttline.com/) | 🇵🇱 🇸🇪 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Faergen](https://www.faergen.dk) | 🇸🇪 🇩🇰 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔
[Color Line](https://www.colorline.com/) | 🇳🇴 🇩🇰 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔

Todo: [Mediterranean](https://wikitravel.org/en/Ferries_in_the_Mediterranean), [Britain](https://wikitravel.org/en/Ferry_routes_to_British_Mainland)


## Contributing

If you want to add another operator, endpoint or module (even in other programming languages) to this list, feel free to send a pull request or leave us a hint at [the issues page](https://github.com/public-transport/european-transport-operators/issues).
