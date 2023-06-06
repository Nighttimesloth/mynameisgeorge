# Building standalone executable (Windows)

## Run `PySilon.bat` and the GUI will appear. Fill in the needed information and click on `Generate source`, then `Compile`

<p align="center"><img src="https://user-images.githubusercontent.com/44233157/210283583-8eed0cdf-0bbe-453c-af16-695d48f6743d.png" /></p><br />

Inside builder, you can `Load configuration` to save time between testing or you can `Load custom...` configuration from desired configuration-file, additionally, you can `Reset` the settings or `Save` them for later. When you `Generate source`, configuration will be automatically saved.  

### Options

- On the right, tick all the modules that you want to use. I would recommend removing webcam if you don't plan on using it, because its libraries take up a lot of space.
- Server ID: The ID of the server that the bot will be on.
- Bot Token: The bots' token from the Discord Application website.
- Emergency tokens: Tokens that will be used as a fallback if your Bot token is deleted by Discord.
- Registry Name: Name of the file in the startup registry. (e.g. PySilon)
- Directory Name: Name of the directory where the malware is stored. (e.g. PySilon)
- Executable Name: The name of the .exe file. (e.g. pysilon.exe)
- Icon: The icon that the executable will use (the little image on it)
  
## Multiple Discord BOT tokens

**You can add more than one BOT-token to malware in case of the first one getting banned by Discord (```Emergency token 1/2```). If first token gets banned, PySilon will automatically run with another one (if you set them in compiler.py)**

<br />

If you encounter any errors, please [open an Issue](https://github.com/mategol/PySilon-malware/issues/new/choose) and we'll be happy to help as soon as possible.

<br />

**Now, everything is ready for a showtime**

# Building standalone executable (Linux)

## Run `PySilon.sh` you will get a few options. Follow them to install wine and to download python inside of wine. Then the GUI should start automatically. Fill in the needed information and click on `Generate source`, then `Compile`

Supported Distros:

- Arch / Arch based (tested)
- Ubuntu (not tested)
- Fedora (not tested)
- Operating systems based on these Distros (not tested)

Unsupported Distros:

- openSUSE
- Nix
- Void
- Debian
- Alpine

If you have a supported Distro and you want to test it, please do and report any errors / feedback about it to us so we can add it to the tested Distros

<p align="center"><img src="https://user-images.githubusercontent.com/44233157/210283583-8eed0cdf-0bbe-453c-af16-695d48f6743d.png" /></p><br />

Inside builder, you can `Load configuration` to save time between testing or you can `Load custom...` configuration from desired configuration-file, additionally, you can `Reset` the settings or `Save` them for later. When you `Generate source`, configuration will be automatically saved.  

### Options

- On the right, tick all the modules that you want to use. I would recommend removing webcam if you don't plan on using it, because its libraries take up a lot of space.
- Server ID: The ID of the server that the bot will be on.
- Bot Token: The bots' token from the Discord Application website.
- Emergency tokens: Tokens that will be used as a fallback if your Bot token is deleted by Discord.
- Registry Name: Name of the file in the startup registry. (e.g. PySilon)
- Directory Name: Name of the directory where the malware is stored. (e.g. PySilon)
- Executable Name: The name of the .exe file. (e.g. pysilon.exe)
- Icon: The icon that the executable will use (the little image on it)
  
## Multiple Discord BOT tokens

**You can add more than one BOT-token to malware in case of the first one getting banned by Discord (```Emergency token 1/2```). If first token gets banned, PySilon will automatically run with another one (if you set them in compiler.py)**

<br />

If you encounter any errors, please [open an Issue](https://github.com/mategol/PySilon-malware/issues/new/choose) and we'll be happy to help as soon as possible.

<br />

**Now, everything is ready for a showtime**