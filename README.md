# Open Data Examples - Hack for Sweden 2019

These Jupyter Notebooks contains examples on how to access open data through APIs. It was made for Hack for Sweden 2019.

If you want to work with the examples during the hack, I recommend using https://jupyter.se where you login with a Google account and get started with the README. You can also run these examples on mybinder.org, but inactivity will shut you down and work wont be saved.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hack-for-sweden/open-data-examples/master?urlpath=%2Flab)

# Examples

## Polisen.se - Get police events
With this API you can get events based on _when_, _where_ and _what_, for more details [read this](https://polisen.se/om-polisen/om-webbplatsen/oppna-data/api-over-polisens-handelser/).

- [polisen-se.ipynb](polisen-se.ipynb) - added by [@salgo60](https://github.com/salgo60)

## Wikidata.org - Get info from the Wikipedia project
Wikidata provides machine readable data from the Wikipedia project, licenced under a Creative Commons "No rights reserved" licence called [CC-0](https://creativecommons.org/share-your-work/public-domain/cc0/).

- [wikidata-org.ipynb](wikidata-org.ipynb) - added by [salgo60](https://github.com/salgo60) along with this [video](https://youtu.be/HrfQioXjGZE)

### Wikidata and Machinelearning
As Wiki is an internatinal project in +300 languages and has a lot of articles, Wikidata is a good start for harvesting data to use in machinelearning
* Example SPARQL queries
    * All [Swedish politicians in the Swedish Goverment](http://tinyurl.com/y4jo4lva)
        * just those with a [twitter account](http://tinyurl.com/y4qb32q9)
* In may started also the [Lexicographical data project](https://www.wikidata.org/wiki/Wikidata:Lexicographical_data/en) with the goal to "describe precisely all words in all languages" in a machinereadable form

## Försäkringskassan - Get statistics
With his API you get statics, for more details [read this](https://oppnadata.se/datamangd/#esc_entry=4778&esc_context=547).
- [Forsakringskassan.ipynb](Forsakringskassan.ipynb) - added by [@salgo60](https://github.com/salgo60)
