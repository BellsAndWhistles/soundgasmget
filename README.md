# SOUNDGASMGET

This script downloads the audio file embeded in the [soundgasm.net](https://soundgasm.net/) url provided. It uses curl to download the html of the page, and wget to download the audio.

## Requirements
* curl - To download the html of the page
* wget - To download the file found by the script
## Installation
Simply curl **soundgasmget** to your **$PATH** and grant it execute permissions.
```{sh}
$ curl https://raw.githubusercontent.com/BellsAndWhistles/soundgasmget/main/soundgasmget -o $HOME/.local/bin/soundgasmget
$ chmod +x $HOME.local/bin/soundgasmget
```
* To update the script, simply download it again using the above command.
* To uninstall the script, simply remove the file.

## License
This project is licensed under [GPL-3.0.](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt)
