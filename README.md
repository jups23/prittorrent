PritTorrent
===========

Build
-----

```
rebar get-deps compile generate
```


TODO
----

* Stats
* ATOM feeds
* Test Miro
* UI: Detect browser language
* Zlib for UI

* Feed summaries: X items, Y torrents
* Recent Torrents excluding Popular Torrents
* render_item styles
* Flattr button on img hover
* <atom:link rel="self>

* Storage app
** Avoid dup connections to 1 HTTP server (IP)
** Fair queueing
** Caching
* URL longener?

* HTTP UA output
* Stats:
** Counters: ULed Swarm+PritTorrent, DLed, Completes
** Gauges: Seeders, Leechers
** DLs by country/client?
* Publisher mode
* rebar release

Future features:

* UDP tracker
* UTP wire protocol
* UI: Wholesome OPML export
* Super-seeding
* Slot queues
* PEX
* DHT support