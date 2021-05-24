---
title: Download files
---

## Linking to files for download

### Download text files as Raw
Regardless of whether you click or right-click > Save As, GitHub's default for text files such as .csv or .txt is to open an editing page as html, rather than the original file.  You can force GitHub to display the raw file using a link like this:
- [GPS locations](https://raw.githubusercontent.com/verdantlearn/gis-refresher-gps-field-obs/master/datasets/waterbeetles_wpts.gpx) as .gpx file (for Monday)

The problem with this solution is that the links are hard-coded rather than relative, so links will need updating if the repo is renamed or forked

### Download text files using <a> link
Instead of linking to the Raw version of the file, you can create an html link and specify that the file should be downloaded rather than displayed:

- <a href="/src/dataset/waterbeetles_wpts.csv" download>GPS locations</a> as .csv file (for Monday) - *doesn't work, takes to parent repo* :grimacing:
- <a href="{{site.baseurl}}/src/dataset/waterbeetles_wpts.csv" download>GPS locations</a> as .csv file (for Monday) **Works!!** Relative url works (in GPS course at least - hard to test in private repo except locally, where behaviour is different), and download box pops up  :smile:



### Downloading pdfs
Github's default is to display in browser
