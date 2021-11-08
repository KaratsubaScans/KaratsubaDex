## からつばSCANS

This is the site where we host the manga that **KaratsubaScans** has translated. This is a very minimal site, only to distribute manga. A dedicated reader webapp may or may not be coming in the future.

### karat-cli
**karat-cli** is a smol tool written in make for writing static html to the site. It can generate rss entries and update chapter lists when a new chapter is released. It also has a mini blog feature that is based off [blogit](https://pedantic.software/git/blogit).

### project structure
the content/ directory stores json data that is used by karat-cli to generate the static html. content/ has two directories, manga/ and blog/, ideally, these two are git modules, so as to keep the git tree of karat-cli separate from content updates (like new chapters) to the site.

