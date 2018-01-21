# WMT16-test-enfi

Test data for the news translation task at [WMT 2016](http://www.statmt.org/wmt16/translation-task.html) for the language pair English-Finnish. The test set contains 3,000 verified translations provided by professional translators. 1,500 sentences are translated from Finnish to English and 1,500 sentences from English to Finnish.

* `original/` - original documents
* `translated/` - translations provided by human translators
* `sgm/` - official WMT test sets in SGML format
* `txt/` - plain text versions of the official WMT test sets
* `mt/` - machine-translated texts

## Finnish original

* 79 documents
* 1,500 sentences
* 16,580 space-separated tokens (wthout proper tokenization)

## English original

* 68 documents
* 1,500 sentences
* 30,945 space-separated tokens (wthout proper tokenization)

## Alternative translations

All 1,500 English sentences have been translated twice by independent translators. They can be used for multi-reference evaluation or tuning.

## License

The package is distribute with the Creative Commons Attribution 4.0 license.

## Acknowledgements

The translation costs were covered by [BAULT](https://kitwiki.csc.fi/twiki/bin/view/BAULT/WebHome), a multidisiplinary research community on Building And Using Language Technology at the University of Helsinki. We would like to thank Anna Missilä and Lingsoft for providing the translations and Maarit Koponen for selecting the Finnish documents to be translated.
