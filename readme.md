# European transport operators

## THIS DOCUMENT IS UNMAINTAINED AND NOT UP TO DATE ANYMORE. CHECK THE [LIST OF EUROPEAN TRANSPORT FEEDS](https://eu.data.public-transport.earth) INSTEAD.


This is a list of european long-distance transport operators, available API endpoints, GTFS feeds and client modules. The long-term goal would be to have [GTFS](https://developers.google.com/transit/gtfs/) / [FPTF](https://github.com/public-transport/friendly-public-transport-format) for every single operator which would allow us to compose a giant european long-distance transport feed. That would be pretty cool, huh? Let's get to work then… 🔨

- [Country feeds](#country-feeds)
- [Train](#train)
- [Coach](#coach)
- [Ferry](#ferry)

## Country feeds

In some countries, [GTFS](https://developers.google.com/transit/gtfs/) feeds covering multiple operators (ideally *all* relevant operators in the country) are available:

| 🏳️ | 🇪🇺 | 🇦🇱 | 🇦🇩 | 🇦🇲 | 🇦🇹 | 🇦🇿 | 🇧🇾 | 🇧🇪 | 🇧🇦 | 🇧🇬 | 🇭🇷 | 🇨🇾 | 🇨🇿 | 🇩🇰 | 🇪🇪 | 🇲🇰 | 🇫🇮 | 🇫🇷 | 🇬🇪 | 🇩🇪 | 🇬🇷 | 🇭🇺 | 🇮🇸 | 🇮🇪 | 🇮🇹 | 🇰🇿 | 🇽🇰 | 🇱🇻 | 🇱🇮 | 🇱🇹 | 🇱🇺 | 🇲🇹 | 🇲🇩 | 🇲🇨 | 🇲🇪 | 🇳🇱 | 🇳🇴 | 🇵🇱 | 🇵🇹 | 🇷🇴 | 🇷🇺 | 🇸🇲 | 🇷🇸 | 🇸🇰 | 🇸🇮 | 🇪🇸 | 🇸🇪 | 🇨🇭 | 🇹🇷 | 🇺🇦 | 🇬🇧 | 🇻🇦 |
| - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| [GTFS](https://developers.google.com/transit/gtfs/) | ❌ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | [✅](https://help.rejseplanen.dk) | ❔ | ❔ | [✅](http://dev.hsl.fi/gtfs.matka/) | [✅](https://navitia.opendatasoft.com/explore/?sort=modified&q=&refine.geographicarea=France) | ❔ | ❌ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | [✅](http://openov.lu/) | ❔ | ❔ | ❔ | ❔ | [✅](https://openov.nl/) | [✅](https://data.norge.no/data/norsk-reiseinformasjon/nasjonale-rutedata-norge) | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | [✅](http://www.trafiklab.se/api) | [✅](http://gtfs.geops.ch/) | ❔ | ❔ | [✅](https://planar.network/projects/feeds) | ❔ |

## Train

See [this map](train-gtfs/readme.md) for an overview of GTFS feed coverage for different national railway operators.

Operator | 🏳️ | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | Stations\* | GTFS-compatible\*\*
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------
[*Interrail\*\*\**](https://www.interrail.eu/) | 🇪🇺 | ❌ | ✅ | ❌ | [✅](https://github.com/juliuste/interrail/) | ❌ | ✅
[DB](https://www.bahn.de) | 🇩🇪 | [✅](http://data.deutschebahn.com/dataset?groups=apis) | ✅ | ❌ | [✅](https://github.com/derhuerst/db-hafas/) | [✅](http://data.deutschebahn.com/dataset/data-stationsdaten) | ✅
[SNCF](http://www.sncf.fr) | 🇫🇷 | [✅](https://www.digital.sncf.com/startup/api) | ✅ | [✅](https://navitia.opendatasoft.com/explore/?sort=modified&q=&refine.geographicarea=France) | [✅](https://github.com/juliuste/sncf) | ❔ | ➖
[CD](https://www.cd.cz/) | 🇨🇿 | ❔ | ✅ | ❔ | ❔ | ❔ | ❔
[ÖBB](http://www.oebb.at) | 🇦🇹 | ❌ | ✅ | [✅](https://data.oebb.at/oebb?dataset=uddi:cd36722f-1b9a-11e8-8087-b71b4f81793a) | [✅](https://github.com/juliuste/oebb) | ❔ | ❔
[SBB](https://www.sbb.ch) | 🇨🇭 | [✅](https://data.sbb.ch/api/v1/documentation) | ➖ | [✅](http://gtfs.geops.ch/) | ❔ | ❔ | ➖
[SJ](https://www.sj.se/) | 🇸🇪 | [✅](http://www.trafiklab.se/api) | ➖ | [✅](http://www.trafiklab.se/api) | ❔ | ❔ | ➖
[NSB](https://www.nsb.no/) | 🇳🇴 | [✅](https://data.norge.no/data/norsk-reiseinformasjon/nasjonale-rutedata-norge) | ➖ | [✅](https://data.norge.no/data/norsk-reiseinformasjon/nasjonale-rutedata-norge) | ❔ | ❔ | ➖
[VR](https://www.vr.fi) | 🇫🇮 | [✅](https://www.digitransit.fi/) | ➖ | [✅](http://dev.hsl.fi/gtfs.matka/) | ❔ | ❔ | ➖
[DSB](https://www.dsb.dk/) | 🇩🇰 | [✅](https://help.rejseplanen.dk/hc/da/articles/214174465-Rejseplanens-API) | ➖ | [✅](https://help.rejseplanen.dk) | ❔ | ❔ | ➖
[NS](https://www.ns.nl/) | 🇳🇱 | [✅](https://www.ns.nl/en/travel-information/ns-api) | ➖ | [✅](https://openov.nl/) | ❔ | [✅](https://www.rijdendetreinen.nl/over/open-data) | ➖
[SNCB](http://www.belgianrail.be/) | 🇧🇪 | [✅](https://api.irail.be/) | ❔ | ❔ | ❔ | ❔ | ❔
[CFL](http://www.cfl.lu/) | 🇱🇺 | ❔ | ❔ | [✅](http://openov.lu/) | ❔ | ❔ | ➖
[CP](https://www.cp.pt) | 🇵🇹 | ❔ | ✅ | [✅](https://gtfs.directory/comboios-de-portugal/) | [✅](https://github.com/juliuste/comboios) | ✅ | ✅
[renfe](http://www.renfe.com/) | 🇪🇸 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[Trenitalia](http://www.trenitalia.com) | 🇮🇹 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[PKP](http://pkp.pl/) | 🇵🇱 | ❔ | ✅ | ❔ | [✅](https://github.com/juliuste/bilkom) | ❔ | ❔
[HŽPP](http://www.hzpp.hr/) | 🇭🇷 | ❔ | ❔ | [✅](https://data.gov.hr/dataset/vozni-red-h-putni-kog-prijevoza-u-gtfs-obliku) | ❔ | ❔ | ❔
[CFR](https://www.cfrcalatori.ro/) | 🇷🇴 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[SŽ](http://www.slo-zeleznice.si) | 🇸🇮 | ❔ | ✅ | ❔ | [✅](https://github.com/juliuste/slovenske-zeleznice) | ✅ | ❌
[LDz](https://www.ldz.lv/) | 🇱🇻 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[Бч](http://www.rw.by/) | 🇧🇾 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[LG](http://www.litrail.lt) | 🇱🇹 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[GR](http://www.railway.ge) | 🇬🇪 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[JSC](http://serbianrailways.com/) | 🇷🇸 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[ŽSR](http://www.slovakrail.sk/) | 🇸🇰 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[EVR](http://www.evr.ee/) | 🇪🇪 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[MÁV](https://www.mavcsoport.hu/) | 🇭🇺 | ❔ | ✅ | [✅](https://gtfs.directory/magyar-allamvasutak/) | [✅](https://github.com/juliuste/mav) | ✅ | ✅
[Irish Rail](http://www.irishrail.ie) | 🇮🇪 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[УЗ](http://www.uz.gov.ua/en/) | 🇺🇦 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[RZD](http://pass.rzd.ru/main-pass/public/en) | 🇷🇺 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[CFM](http://www.railway.md/) | 🇲🇩 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[BDZ](http://www.bdz.bg) | 🇧🇬 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[TrainOSE](http://www.trainose.gr/) | 🇬🇷 | ❔ | ✅ | [✅](http://www.trainose.gr/en/gtfs/) | [✅](https://github.com/juliuste/train-ose) | ✅ | ❌
[TCDD](http://www.tcdd.gov.tr/) | 🇹🇷 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[МЖ](http://www.mzi.mk/) | 🇲🇰 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[Trainkos](http://www.trainkos.com/) | 🇽🇰 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[ŽPCG](http://www.zcg-prevoz.me/) | 🇲🇪 | ❔ | ❔ | ❔ | [✅](https://github.com/juliuste/zpcg) | ✅ | ❌
[ŽFBH](http://www.zfbh.ba/) | 🇧🇦 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[ADY](https://ady.az/) | 🇦🇿 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[KTZ](http://www.railways.kz/) | 🇰🇿 | ❔ | ❔ | ❔ | ❔ | ❔ | ❔
[RDG](http://www.raildeliverygroup.com/) | 🇬🇧 | ❔ | ❔ | [✅](https://planar.network/projects/feeds) | ❔ | ❔ | ❔
[Eurostar](http://www.eurostar.com/) | 🇬🇧 🇫🇷 | ❔ | ❔ | [✅](https://planar.network/projects/feeds) | ❔ | ❔ | ❔

\*Complete list of all stations available (not just search-based)

\*\*API provides all data required to generate a GTFS feed (if there's no official feed)

\*\*\*Not an operator, still interesting though

🔍 Results only for a specific search query

Missing countries: 🇦🇱 🇦🇲 🇸🇲 🇻🇦

## Coach

Operator | 🏳️ | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | Stations\* | GTFS-compatible\*\*
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------
[FlixBus](https://www.flixbus.com/) | 🇩🇪 🇪🇺 | ❌ | ✅ | [✅](http://data.ndovloket.nl/flixbus/) | [✅](https://github.com/juliuste/meinfernbus) | ✅ | ➖
[Eurolines (DE)](https://www.eurolines.de) | 🇩🇪 🇪🇺 | ❌ | ✅ | ❔ | [✅](https://github.com/juliuste/eurolines-de) | ❔ | ❔
[Ouibus](https://www.ouibus.com/) | 🇫🇷 🇪🇺 | [✅](https://api.idbus.com/) | ✅ | [✅](https://api.idbus.com/#gtfs-file) | [✅](https://github.com/juliuste/ouibus) | ❔ | ❔
[MegaBus](https://uk.megabus.com/)\*\*\* | 🇬🇧 🇪🇺 | ❔ | ❔ | [✅](https://planar.network/projects/feeds) | ❔ | ❔ | ❔
[Deinbus](https://www.deinbus.de/) | 🇩🇪 🇪🇺 | ❌ | ✅ | ❔ | [✅](https://github.com/juliuste/deinbus) | ❔ | ❔
[Ecolines](https://ecolines.net) | East 🇪🇺 | ❌ | ❔ | ❔ | [✅](https://github.com/juliuste/ecolines) | ❔ | ❔
[LuxExpress](https://luxexpress.eu) | East 🇪🇺 | ❌ | ❔ | ❔ | ❌ | ❔ | ❔
[Nettbuss](https://www.nettbuss.se/) | 🇸🇪 🇳🇴 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[RegioJet](https://www.regiojet.com/) | 🇨🇿 🇸🇰 🇪🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔

\*Complete list of all stations available (not just search-based)

\*\*API provides all data required to generate a GTFS feed

\*\*\*Part of the national coach service feed (NCSD)

## Ferry

Operator | 🏳️ | API | Inofficial API | [GTFS](https://developers.google.com/transit/gtfs/) | JS | Stations\* | GTFS-compatible\*\*
-------- | --------- | --- | -------------- | ---- | -- | --------- | ------
[Stena Line](https://www.stenaline.de/) | North, Baltic | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[DFDS](https://www.dfdsseaways.com/) | North, Baltic | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Scandlines](https://www.scandlines.com/) | 🇸🇪 🇩🇰 🇩🇪 | ❌ | ❔ | ❔ | ❌ | ❔ | ❔
[Finnlines](https://www.finnlines.com/) | 🇫🇮 🇸🇪 🇩🇪 | ❌ | ✅ | ❔ | ❌ | ❔ | ❔
[tallink / Silja Line](https://www.tallink.com/) | 🇸🇪 🇫🇮 🇪🇪 🇱🇻 | ❌ | ✅ | ❔ | [✅](https://github.com/juliuste/tallink) | ❔ | ❔
[Viking Line](http://www.vikingline.fi/) | 🇫🇮 🇪🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Wasa Line](https://www.wasaline.com/) | 🇸🇪 🇫🇮 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[St. Peter Line](https://stpeterline.com/) | 🇸🇪 🇫🇮 🇪🇪 🇷🇺 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Polferries](http://polferries.pl/) | 🇵🇱 🇸🇪 🇩🇰 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Unity Line](https://www.unityline.pl/) | 🇵🇱 🇸🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[TT Line](https://ttline.com/) | 🇵🇱 🇸🇪 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Faergen](https://www.faergen.dk) | 🇸🇪 🇩🇰 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔
[Color Line](https://www.colorline.com/) | 🇳🇴 🇩🇰 🇩🇪 | ❔ | ❔ | ❔ | ❌ | ❔ | ❔

\*Complete list of all stations available (not just search-based)

\*\*API provides all data required to generate a GTFS feed

Todo: [Mediterranean](https://wikitravel.org/en/Ferries_in_the_Mediterranean), [Britain](https://wikitravel.org/en/Ferry_routes_to_British_Mainland)

## Contributing

Note that, by participating in this project, you commit to the [code of conduct](code-of-conduct.md). If you want to add another operator, endpoint or module (even in other programming languages) to this list, feel free to send a pull request or leave us a hint at [the issues page](https://github.com/public-transport/european-transport-operators/issues).
