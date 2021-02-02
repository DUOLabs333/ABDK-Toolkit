# ABDK-Toolkit-Offline
Offline version of ABDK Consulting's Toolkit (https://toolkit.abdk.consulting/)

## Why I made this
On the toolkit's page, they had a link to the GitHub, leading to the assumption that it is open sourced. However, on the [page](https://github.com/abdk-consulting/abdk-toolkit), there's nothing there. So, I took it upon myself to create a WARC file version of this to be used offline.

## How to use
1. Download the repository
1. Open a terminal
1. `cd` into the folder where you downloaded it
1. `cd` into the "toolkit.abdk.consulting" in that folder
1. In the subfolder, type `python -m http.server`
1. Open [http://localhost:8000](http://localhost:8000). It should load and you can use it like normal.
