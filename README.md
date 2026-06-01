# SELect 5 RSE

## Custom Required Stream Expression to use with TamTaro's Template

Simple enough to understand. It will always display the top five streams, and _**only**_ the top five streams, based on their resolution, then quality, then visual and audio tags, and finally the stream expression scores, after all of TamTaro's and Vidhin's marvelous handiwork.

> [!IMPORTANT]
>
> In order for this to work as intended, you must edit the sorting order as follows:
> - Library
> - SeaDex
> - Resolution
> - Quality
> - Stream Expressions
> - Visual Tag
> - Audio Tag
> - Stream Expression Score
> - Everything else...

## Formatter
I built an AIOStreams formatter template as a companion for the new badge integration feature on Nuvio going for a clean yet informative aesthetic. 

It supports cached/uncached display, regex scoring, library display (the play symbol before the file name is filled if it's in the library and only an outline if it's not), and displaying all major cuts and editions and audio languages. 

You should use the below JSON as the import URL for the badges for best results.
```
https://raw.githubusercontent.com/9mousaa/BetterFormatter/main/presets/mono-bgb-sep-nodv.json
```

![Preview](./formatterpreview.png)
