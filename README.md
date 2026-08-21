# Awesome Memento with stars

<!--lint ignore awesome-list-item-->

A list of things related to software, literature, and other content for Memento ([RFC7089](https://tools.ietf.org/html/rfc7089)).

## Contents

* [Software](#software)
  * [Web Browser Extensions](#web-browser-extensions)
  * [Mobile Apps](#mobile-apps)
  * [Command-line Clients](#command-line-clients)
  * [Server-side Enablers](#server-side-enablers)
  * [Web Archive Replay](#web-archive-replay)
  * [Additional Tools](#additional-tools)
* [Literature](#literature)
  * [Peer-Reviewed Publications](#peer-reviewed-publications)
  * [Blog Posts](#blog-posts)

## Software

### Web Browser Extensions

* Mink - Google Chrome Extension ([src](https://github.com/machawk1/mink) ⭐ 58 | 🐛 95 | 🌐 JavaScript | 📅 2025-08-27, [Web Store](https://chrome.google.com/webstore/detail/mink-integrate-live-archi/jemoalkmipibchioofomhkgimhofbbem))
* Memento Time Travel - Google Chrome extension and Mozilla Firefox Add-On ([src](https://github.com/mementoweb/memento_chrome) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2021-03-15, [Web Store](https://chrome.google.com/webstore/detail/memento/jgbfpjledahoajcppakbgilmojkaghgm), [Add-On Store](https://addons.mozilla.org/en-US/firefox/addon/memento-timetravel/))
* MementoFox - Firefox Add-On ([src](https://code.google.com/archive/p/mementofox/), deprecated)

### Mobile Apps

* Memento-Browser - View web archives in the time dimension on Android ([src](https://github.com/machawk1/mementobrowser-android) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2014-08-06)
* MementoBrowser-ios - View web archives in the time dimension on iOS ([src](https://github.com/machawk1/mementobrowser-ios) ⭐ 1 | 🐛 0 | 🌐 Objective-C | 📅 2014-08-06)
* Mobile Mink - View and create archived versions of mobile and desktop pages on Android ([src](https://github.com/oduwsdl/mobilemink) ⭐ 1 | 🐛 16 | 🌐 Java | 📅 2023-09-14)

### Command-line Clients

* py-memento-client ([src](https://github.com/mementoweb/py-memento-client) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2018-03-05) - Python client to interface with Memento entities.
* archive.is - ([src](https://github.com/qvint/archive.is) ⭐ 20 | 🐛 5 | 🌐 JavaScript | 📅 2016-01-28, [npm](https://www.npmjs.com/package/archive.is)) - Memento-based API for [archive.is](http://archive.is/) in JavaScript
* memento-cli - ([src](https://github.com/edsu/memento-cli) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-06-04) - A command line tool interacting with Memento (RFC 7089) supporting web archives, such as the Internet Archive's Wayback Machine
* memento-client ([src](https://github.com/jarofghosts/memento-client) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2017-07-31, [npm](https://www.npmjs.com/package/memento-client)) - JavaScript client to interface with Memento services
* Wasteback Machine - ([src](https://github.com/overbrowsing/wasteback-machine) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-24, [npm](https://www.npmjs.com/package/@overbrowsing/wasteback-machine)) - JavaScript library for analyzing archived web pages, measuring their size and composition to support retrospective, quantitative web research
* mcurl ([src](https://github.com/aalsum/mcurl) ⭐ 4 | 🐛 0 | 🌐 Perl | 📅 2013-05-08) - Command Line Memento Client (perl)

### Server-side Enablers

* MemGator ([src](https://github.com/oduwsdl/memgator) ⭐ 80 | 🐛 48 | 🌐 Go | 📅 2026-04-09) - Memento Aggregator written in Go.
* TimeGate ([src](https://github.com/mementoweb/timegate) ⭐ 45 | 🐛 8 | 🌐 Python | 📅 2020-05-04) - Python and uWSGI script to intercept requests for resources to make them Memento-compatible.
* wordpress-memento-plugin - ([src](https://github.com/pastpages/wordpress-memento-plugin) ⚠️ Archived) - Add Memento support to [WordPress](https://wordpress.com/) sites.
* django-memento-framework ([src](https://github.com/pastpages/django-memento-framework) ⚠️ Archived) - Add Memento support to [Django](https://www.djangoproject.com/) applications.
* TimeStitch Memento Aggregator ([src](https://github.com/lanl/TimeStitch-Memento-Aggregator) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-01-12) - Memento Aggregator written in Go from Los Alamos National Laboratory.
* invenio-memento - ([src](https://github.com/inveniosoftware/invenio-memento) ⚠️ Archived) - Add Memento support to [Invenio](http://invenio-software.org/) sites.
* Linked Data
  * [Linked Data Fragments Server](https://github.com/LinkedDataFragments/Server.js/) ⭐ 181 | 🐛 59 | 🌐 JavaScript | 📅 2026-08-20 - Server-side component offering [Triple Pattern Fragments](http://www.hydra-cg.com/spec/latest/triple-pattern-fragments/) and different versions of an evolving dataset using Memento.
  * [Apache Marmotta](http://marmotta.apache.org/) - An open implementation of the W3C Linked Data Platform specification, which supports versioning and access to versions compliant with the Memento protocol.
* MediaWiki Extensions - Add Memento support to [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) instances:
  * [Extension: Memento](https://www.mediawiki.org/wiki/Extension:Memento) - Provides complete Memento support.
  * [Extension: MementoHeaders](https://www.mediawiki.org/wiki/Extension:MementoHeaders) - Provides only the necessary HTTP headers for minimal Memento support.
* Memento Tracer ([site](http://tracer.mementoweb.org/), no public prototype) - server-side processor to capture web publications for archival purposes.
* mementoweb - ([npm](https://www.npmjs.com/package/mementoweb)) - JavaScript module to add Memento functionality to [Express](http://expressjs.com/) projects.

### Web Archive Replay

* pywb ([src](https://github.com/webrecorder/pywb) ⭐ 1,690 | 🐛 182 | 🌐 JavaScript | 📅 2026-04-10) - Python-based replay engine.
* InterPlanetary Wayback (ipwb) ([src](https://github.com/oduwsdl/ipwb) ⭐ 655 | 🐛 160 | 🌐 Python | 📅 2026-07-24) - Integration of WARCs with IPFS, supports Memento in bundled replay system.
* OpenWayback ([src](https://github.com/iipc/openwayback) ⭐ 525 | 🐛 105 | 🌐 Java | 📅 2024-01-03) - De facto web archive replay engine with the ability to provide Memento headers to archived resources. Written in Java.

### Additional Tools

* Comunica ([src](https://github.com/comunica/comunica) ⭐ 577 | 🐛 80 | 🌐 TypeScript | 📅 2026-08-21) - A knowledge graph querying framework for JavaScript with [Memento support](https://github.com/comunica/comunica/pull/195) ⭐ 577 | 🐛 80 | 🌐 TypeScript | 📅 2026-08-21.
* Memento Validator ([src](https://github.com/lanl/memento-validator) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2021-10-28) - Memento validator toolkit lets you validate your Memento implementation

## Literature

### Peer-Reviewed Publications

* [IETF RFC7089](https://www.rfc-editor.org/rfc/rfc7089) - HTTP Framework for Time-Based Access to Resource States -- Memento.
* [Exploiting the Untapped Functional Potential of Memento Aggregators Beyond Aggregation](https://link.springer.com/article/10.1007/s00799-023-00391-0) - M. Kelly - IJDL - March 2024.
* [The Memento Tracer Toolset for Human-Guided Focused Crawling of Dynamic Web](https://ieeexplore.ieee.org/document/10265943) - L. Balakireva et al. - JCDL - 2023.
* [You Call This Archaeology? Evaluating Web Archives for Reproducible Web Security Measurements](https://swag.cispa.saarland/papers/hantke2023archaeology.pdf) - F. Hantke et al. - ACM CCS - 2023.
* [Interoperability for Accessing Versions of Web Resources with the Memento Protocol](https://sobre.arquivo.pt/wp-content/uploads/The-Past-Web_-exploring-web-archives-preprint.pdf#page=123) - S. Jones et al. - The Past Web - 2021.
* [HTTP Extensions for the Management of Highly Dynamic Data Resources](https://link.springer.com/chapter/10.1007/978-3-030-77385-4_13) - L. Gleim et al. - ESWC - May 2021.
* [The Off-Topic Memento Toolkit](https://www.cs.odu.edu/~mln/pubs/ipres-2018/ipres-2018-jones-off-topic.pdf) - S. Jones et al. - iPres - September 2018.
* [A Framework for Aggregating Private and Public Web Archives](https://dl.acm.org/citation.cfm?id=3197045) - M. Kelly et al. - JCDL - June 2018.
* [Focused Crawl of Web Archives to Build Event Collections](https://dl.acm.org/citation.cfm?id=3201085) - M. Klein et al.
* [Impact of URI Canonicalization on Memento Count](http://ieeexplore.ieee.org/abstract/document/7991601/) - M. Kelly et al. - JCDL - June 2017.
* [Detecting off-topic pages within TimeMaps in Web archives](http://link.springer.com/article/10.1007/s00799-016-0183-5) - Y. Anwar et al. - IJDL - July 2016.
* [MemGator - A Portable Concurrent Memento Aggregator: Cross-Platform CLI and Server Binaries in Go](http://dl.acm.org/citation.cfm?id=2925452) - S. Alam and M. Nelson - JCDL - June 2016.
* [Routing Memento Requests Using Binary Classifiers](http://dl.acm.org/citation.cfm?id=2910899) - N. Bornand et al. - JCDL - June 2016.
* [Only One Out of Five Archived Web Pages Existed as Presented](http://dl.acm.org/citation.cfm?id=2791044) - S. Ainsworth et al. - Hypertext - September 2015.
* [Mobile Mink: Merging Mobile and Desktop Archived Webs](http://dl.acm.org/citation.cfm?id=2756956) - W. Jordan et al. - JCDL - June 2015.
* [Mink: Integrating the Live and Archived Web Viewing Experience Using Web Browsers and Memento](http://dl.acm.org/citation.cfm?id=2740872) - M. Kelly et al. - JCDL - September 2014.
* [Not All Mementos Are Created Equal: Measuring The Impact Of Missing Resources](http://dl.acm.org/citation.cfm?id=2740826) - J. Brunelle et al. - JCDL - September 2014.
* [Evaluating sliding and sticky target policies by measuring temporal drift in acyclic walks through a web archive](http://link.springer.com/article/10.1007/s00799-014-0120-4) - S. Ainsworth and M. Nelson - IJDL - August 2014.
* [Global Web Archive Integration with Memento](https://dl.acm.org/citation.cfm?doid=2232817.2232900) - R. Sanderson - JCDL - June 2012.

### Blog Posts

* September 20, 2024 - [Some URLs Are Immortal, Most Are Ephemeral](https://ws-dl.blogspot.com/2024/09/2024-09-20-some-urls-are-immortal-most.html)
* November 1, 2016 - [Fixing broken links in Wikipedia](http://blog.dshr.org/2016/11/fixing-broken-links-in-wikipedia.html)
* September 6, 2016 - [Memento at W3C](http://blog.dshr.org/2016/09/memento-at-w3c.html)
* August 25, 2016 - [Evanescent Web Archives](http://blog.dshr.org/2016/08/evanescent-web-archives.html)
* August 23, 2016 - [Content Negotiation and Memento](http://blog.dshr.org/2016/08/content-negotiation-and-memento.html)
* January 8, 2016 - [Aggregating Web Archives](http://blog.dshr.org/2016/01/aggregating-web-archives.html)
* April 23, 2013 - [Making Memento Successful](http://blog.dshr.org/2013/04/making-memento-succesful.html)
* March 5, 2013 - [Re-thinking Memento Aggregation](http://blog.dshr.org/2013/03/re-thinking-memento-aggregation.html)
* January 3, 2011 - [Memento & the Marketplace for Archiving](http://blog.dshr.org/2011/01/memento-marketplace-for-archiving.html)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-21._
