# speedtestAU

This is an Australian extract of Speedtest Open data available at Amazon WS (link below - opendata.aws).

Citation: Ferrers, Richard; Index, Speedtest Global (2020). Speedtest Open Data - Australia(NZ) 2020/21/22/23; Q220 - Q423 extract by Qtr. figshare. Dataset. https://doi.org/10.6084/m9.figshare.13370504.v33

AWS data licence is "CC BY-NC-SA 4.0", so use of this data must be:

- non-commercial (NC)

- reuse must be share-alike (SA)(add same licence).

This restricts the standard CC-BY Figshare licence.
Data files (*.geojson) are over 25Mb and too big for Github. See links at Figshare, link below or see citation.
Can download to local drive and load into Jupyter.<br>
Load data with: au2_tiles = gp.read_file("/mydir/speedtest-AUS-Q323.geojson")<br>
Plot with: au2_tiles.centroid.plot()
Sample NZ data provided, since under 10Mb.

This github will provide Binder access to Jupyter Notebook from Figshare.

Data files (>25MB) at: https://doi.org/10.6084/m9.figshare.13370504<br>
NB: Error: Overflows 8GB RAM Binderhub container provided with global Speedtest data file (3GB)

[![Binder](https://binderhub.rc.nectar.org.au/badge_logo.svg)](https://binderhub.rc.nectar.org.au/v2/gh/areff2000/speedtestAU/HEAD?labpath=Speedtest-workflow-import-v2.ipynb)

Added Binder from ARDC service: https://binderhub.rc.nectar.org.au
