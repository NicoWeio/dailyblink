[![Actions Status](https://github.com/ptrstn/dailyblink/workflows/Python%20package/badge.svg)](https://github.com/ptrstn/dailyblink/actions)
[![Build Status](https://travis-ci.com/ptrstn/dailyblink.svg?branch=master)](https://travis-ci.com/ptrstn/dailyblink)
[![codecov](https://codecov.io/gh/ptrstn/dailyblink/branch/master/graph/badge.svg)](https://codecov.io/gh/ptrstn/dailyblink)

# Daily Blinkist downloader

Downloads the [Free Daily](https://www.blinkist.com/de/nc/daily) from Blinkist. No Login required.
Both German and English.

## Installation

Install [Python 3.6+](https://www.python.org/) and run:

```bash
pip install --user git+https://github.com/ptrstn/dailyblink
```

## Usage

```bash
dailyblink
```

All blinks are saved in the current working directory. One folder per book.

Example:

```bash
$ pwd
/home/.../Musik/DailyBlinks
$ dailyblink
Downloading the free daily Blinks...

english (en):
Unlocking Creativity - Michael Roberto

Saving book text...
Saving book cover...
Saving audio track #1 - What’s in it for me? Discover the six mi...
Saving audio track #2 - Counteract the linear mind-set by incorp...
Saving audio track #3 - Avoid the benchmarking mind-set by striv...
Saving audio track #4 - Steer clear of the prediction mind-set b...
Saving audio track #5 - Psychological safety within a company is...
Saving audio track #6 - The focus mind-set can be avoided by tak...
Saving audio track #7 - Naysayers are most effective in pairs an...
Saving audio track #8 - Final summary...

german (de):
Warum ich nicht länger mit Weißen über Hautfarbe spreche - Reni Eddo-Lodge

Saving book text...
Saving book cover...
Saving audio track #1 - Was drin ist für dich: Strukturellen Ras...
Saving audio track #2 - Die Kommunikationskluft zwischen Weißen ...
Saving audio track #3 - Der Rassismus in Großbritannien wurzelt ...
Saving audio track #4 - Wir müssen uns auch mit der „schwarzen G...
Saving audio track #5 - Struktureller Rassismus führt zu ungleic...
Saving audio track #6 - Struktureller Rassismus zeigt sich auch ...
Saving audio track #7 - Der Mangel an schwarzen Heldenfiguren in...
Saving audio track #8 - Wir brauchen einen Feminismus, der sich ...
Saving audio track #9 - Die britische Politik ignoriert den Rass...
Saving audio track #10 - Zusammenfassung...

All blinks were saved under /home/.../Musik/DailyBlinks
```
