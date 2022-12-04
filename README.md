# SOUNDGASMGET

This script downloads the audio file embeded in the soundgasm url provided. It uses curl to download the html of the page, and wget to download the audio.

## Requirements
* curl - To download the html of the page
* wget - To download the file found by the script
## Installation
Simply curl **soundgasmget** to your **$PATH** and grant it execute permissions.
```{sh}
$ curl https://raw.githubusercontent.com/BellsAndWhistles/soundgasmget/main/soundgasmget -o $HOME/.local/bin/soundgasmget
$ chmod +x $HOME.local/bin/soundgasmget
```
