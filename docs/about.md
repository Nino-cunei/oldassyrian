<img src="images/logo.png" align="left"/>
<img src="images/ninologo.png" align="right" width="20%"/>

The Old Assyrian corpus
==============================

This repo is about the digital processing of the transliterations of
cuneiform tablets from the Old Assyrian period.

Cuneiform tablets
=================

Cuneiform tablets have been photographed, and transliterated
in [ATF](http://oracc.museum.upenn.edu/doc/help/editinginatf/cdliatf/index.html)
files, in which the marks on a tablet are represented by ascii characters.

While the ATF descriptions preserve an awesome amount of precise information
about the marks that are visible in the clay and their spatial structure, it is
not easy to process that information. Simple things are hard: counting,
aggregating, let alone higher level tasks such as clustering, colocation, and
other statistical operations.

That is why we have converted the transliterations to an other format,
[Text-Fabric](https://github.com/annotation/text-fabric)
, which is optimized for processing, adding data and sharing it.

Corpus
------

We have chosen the
Old Assyrian documents
(2000-1600 BC) as the third corpus for testing our approach. This is
*cuneiform* corpus of ca. 4775 documents (tablets and envelopes) with legible inscriptions.

The previous cuneiform corpora that we have brought into Text-Fabric are:
*   proto-cuneiform [Uruk](https://github.com/Nino-cunei/uruk/blob/master/docs/about.md) corpus.
*   cuneiform [OldBabylonian](https://github.com/Nino-cunei/oldbabylonian/blob/master/docs/about.md) corpus.

Provenance
----------

We have downloaded transliterations and images from the **Cuneiform Digital
Library Initiative** [CDLI](https://cdli.ucla.edu).
It has compiled a rich source of
data, available to the public, visible on its website, and large portions are
conveniently downloadable. We are indebted to the creators and maintainers of
the CDLI website.

### Transliterations

On the [search page](https://cdli.ucla.edu/search/search.php) we performed a
search with `Old Assyrian` in the *Chronology - period* field.
On the results page, we have chosen `Download all text`.

The downloaded files contain metadata and transliterations.

We use a dozen or so of the metadata fields, but the focus is on the transliterations.

We have a
[specification](https://github.com/Nino-cunei/tfFromAtf/blob/master/docs/transcription.md)
of the transcription format and how we model the text in Text-Fabric.
