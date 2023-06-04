# Building standalone executable

## Run `PySilon.bat` and GUI will appear. Fill the needed information and click on `Generate source`, then `Compile`

<p align="center"><img src="https://user-images.githubusercontent.com/44233157/210283583-8eed0cdf-0bbe-453c-af16-695d48f6743d.png" /></p><br />

Inside builder, you can `Load configuration` to save time between testing or you can `Load custom...` configuration from desired configuration-file, additionally, you can `Reset` the settings or `Save` them for later. When you `Generate source`, configuration will be automatically saved.  
If you (for some reason) cannot use GUI, you must use the obsolete way (deprecated) or wait for me to publish the CLI update of builder

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

If you encounter any errors, please [open an Issue](https://github.com/mategol/PySilon-malware/issues/new/choose) and I'll be happy to help as soon as possible.

<br />

**Now, everything is ready for a showtime**