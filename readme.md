# European transport JavaScript modules

This is a list of european long-distance transport operators, available API endpoints, GTFS feeds and client modules. The long-term goal would be to have [GTFS](https://developers.google.com/transit/gtfs/) / [FPTF](https://github.com/public-transport/friendly-public-transport-format) for every single operator which would allow us to compose a giant european long-distance transport feed. That would be pretty cool, huh? Let's get to work then… 🔨

## Train

Operator | Countries | API | Inofficial API | GTFS | JS
-------- | --------- | --- | -------------------- | ---- | --
[*Interrail\**](https://www.interrail.eu/) | 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/interrail/)
[DB](https://www.bahn.de) | 🇩🇪 🇪🇺 | [✅](http://data.deutschebahn.com/dataset?groups=apis) | ✅ *todo* | ❌ | [✅](https://github.com/derhuerst/db-hafas/)
[SNCF](http://www.sncf.fr) | 🇫🇷 🇪🇺 | [✅](https://www.digital.sncf.com/startup/api) | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/sncf)
[CD](https://www.cd.cz/) | 🇨🇿 🇪🇺 | ❔ | ❔ | ❔ | ❌
[ÖBB](http://www.oebb.at) | 🇦🇹 🇪🇺 | ❌ | ❔ | ❔ | ❌
[SBB](https://www.sbb.ch) | 🇨🇭 🇪🇺 | [✅](https://data.sbb.ch/api/v1/documentation) | ❔ | ❔ | ❌
[SJ](https://www.sj.se/) | 🇸🇪 🇪🇺 | ❔ | ❔ | ❔ | ❌
[NSB](https://www.nsb.no/) | 🇳🇴 🇪🇺 | ❔ | ❔ | ❔ | ❌
[VR](https://www.vr.fi) | 🇫🇮 🇪🇺 | ❔ | ❔ | ❔ | ❌
[DSB](https://www.dsb.dk/) | 🇩🇰 🇪🇺 | ❔ | ❔ | ❔ | ❌
[NS](https://www.ns.nl/) | 🇳🇱 🇪🇺 | ❔ | ❔ | ❔ | ❌
[SNCB](http://www.belgianrail.be/) | 🇧🇪 🇪🇺 | ❔ | ❔ | ❔ | ❌
[CFL](http://www.cfl.lu/) | 🇱🇺 🇪🇺 | ❔ | ❔ | ❔ | ❌
[CP](https://www.cp.pt) | 🇵🇹 🇪🇺 | ❔ | ❔ | ❔ | ❌
[renfe](http://www.renfe.com/) | 🇪🇸 🇪🇺 | ❔ | ❔ | ❔ | ❌
[Trenitalia](http://www.trenitalia.com) | 🇮🇹 🇪🇺 | ❔ | ❔ | ❔ | ❌
[PKP](http://pkp.pl/) | 🇵🇱 🇪🇺 | ❔ | ❔ | ❔ | ❌

\*Not an operator, still interesting though

## Coach

Operator | Countries | API | Inofficial API | GTFS | JS
-------- | --------- | --- | -------------------- | ---- | --
[FlixBus](https://www.flixbus.com/) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/meinfernbus)
[Eurolines (DE)](https://www.eurolines.de) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/eurolines-de)
[PolskiBus](http://www.polskibus.com) | 🇵🇱 🇪🇺 | ❌ | ❔ | ❔ | ❌
[Ouibus](https://www.ouibus.com/) | 🇫🇷 🇪🇺 | [✅](https://api.idbus.com/) | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/ouibus)
[Deinbus](https://www.deinbus.de/) | 🇩🇪 🇪🇺 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/deinbus)
[Ecolines](https://ecolines.net) | 🇪🇺 🇱🇻 🇱🇹 🇪🇪 🇺🇦 🇵🇱 🇷🇺 | ❌ | ❔ | ❔ | ❌
[LuxExpress](https://luxexpress.eu) | 🇪🇺 🇱🇻 🇱🇹 🇪🇪 🇵🇱 🇷🇺 | ❌ | ❔ | ❔ | ❌
[Nettbuss](https://www.nettbuss.se/) | 🇸🇪 🇳🇴 | ❔ | ❔ | ❔ | ❌
[RegioJet](https://www.regiojet.com/) | 🇨🇿 🇸🇰 🇪🇺 | ❔ | ❔ | ❔ | ❌

## Ferry

Operator | Countries | API | Inofficial API | GTFS | JS
-------- | --------- | --- | -------------------- | ---- | --
[Stena Line](https://www.stenaline.de/) | 🇸🇪 🇩🇰 🇳🇴 🇩🇪 🇵🇱 🇪🇪 🇱🇻 🇫🇷 🇬🇧 🇮🇪 🇳🇱 | ❌ | ❌ | ❔ | ❌
[Scandlines](https://www.scandlines.com/) | 🇸🇪 🇩🇰 🇩🇪 | ❌ | ❌ | ❔ | ❌
[Finnlines](https://www.finnlines.com/) | 🇫🇮 🇸🇪 🇩🇪 | ❌ | ✅ *todo* | ❔ | ❌
[tallink / Silja Line](https://www.tallink.com/) | 🇸🇪 🇫🇮 🇪🇪 🇱🇻 | ❌ | ✅ *todo* | ❔ | [✅](https://github.com/juliuste/tallink)


## Contributing

If you want to add another operator, endpoint or module (even in other programming languages) to this list, feel free to send a pull request or leave us a hint at [the issues page](https://github.com/public-transport/european-transport-operators/issues).
