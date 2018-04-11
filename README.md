# Montreal CryptoParty Slides

## Description

This repository follows the spirit of [Cryptoparty/slides](https://github.com/cryptoparty/slides). We are using their format and tools outlined there and hope to achieve the same ends -- creating a universal set of slides to introduce cryptography concepts at cryptoparties. 

Our cryptoparties emphasize social justice and are targeted toward marginalized groups and the problems they face. As such, the content tends to be more niche and pragmatic than introductions to cryptography usually are. For slides that are more generic and academic, we encourage you to visit the parent repo.

All slides should be considered as licensed under a **CC 0 Public Domain** license. All source code is available under a **GPLv3** license. 

The licensing for the slides contained in the original repo was not clear so they have been removed.

## Layout

To make navigation easier the directories are organized as follows:

    slides/<topic>/<language>

## Producing slide shows with Pandoc

```bash
$ cd /slides/intro/en/
$ pandoc -t slidy -s intro.md -o intro.html
$ cd /slides/otr/en/
$ pandoc -t slidy -s otr.md -o otr.html
$ cd /slides/risk/en/
$ pandoc -t slidy -s risk.md -o risk.html
```

This produces an HTML + javascript slide presentation that can be viewed via a web browser.

More information here [http://johnmacfarlane.net/pandoc/README.html#producing-slide-shows-with-pandoc](http://johnmacfarlane.net/pandoc/README.html#producing-slide-shows-with-pandoc)
