<div align="center">
<img src="favicon.ico" alt="MCJS" width="100" height="100"/>
</div>
<h1 align="center">MClassicalJS</h1>
<div align="center">

Minecraft Classic JS hosted on GitHub, open-source, with an offline version included!

[![Stars](https://img.shields.io/github/stars/SSMG4/MClassicalJS?style=social)](https://github.com/SSMG4/MClassicalJS)
[![Issues & Submissions](https://img.shields.io/github/issues/SSMG4/MClassicalJS)](https://github.com/SSMG4/MClassicalJS/issues)
[![GitHub Pages](https://img.shields.io/badge/Live%20Site-Online-blue?logo=github)](https://ssmg4.github.io/MClassicalJS)

>All assets originating from [classic.minecraft.net](https://classic.minecraft.net) are strictly owned and copyrighted by [Mojang Studios™](https://minecraft.net) and are to be credited in any circumstances. Mojang Studios™ is a trademark of [Microsoft Corporation](https://www.microsoft.com).

This project aims to make [classic.minecraft.net](https://classic.minecraft.net) open-source (kinda). Since the assets used by Minecraft Classic JS werent publicly made available by Mojang Studios™, i decided to do so by retreiving each asset manually via [Firefox](https://firefox.com/). Now, you can do anything with it as long as you fully credit Mojang Studios™. You can do stuff like custom texture packs! Or edit the JavaScript code, change blocks, anything!

## Local Usage
If you want to play Minecraft Classic JS offline/locally, you're gonna have to choose between fully local or server local.
### Fully Local
If you want to play fully locally without any drama, i would recommend using [Firefox](https://firefox.com/) as most browsers like Chrome, Edge, Opera, Safari... seized or did not have support for loading Web Workers from ```file://```.
#### Firefox
* Go to the address bar and enter: about:config
* Search for: security.fileuri.strict_origin_policy
* Set it to false (default is true).
* Restart Firefox. (optional)
### Server Local
Server local basically starts a local server at ```http://localhost:PORT``` or whatever your chosen port number is.
#### Tutorial
- Clone the repository using ```git``` or download it as a ZIP file
- Run ```start-server.bat``` or use the command ```http-server``` in the project's directory.
- Open ```localhost:8080``` in your preferred browser
## Online Usage
If you want to play Minecraft Classic JS online, just go to [this website](https://ssmg4.github.io/MClassicalJS)!
