Please note: this is a mirror of the original SHAIO from GetRaid which I use so much it's not even funny, but I learned very recently (march 19th 2023) that it was archived in Jan. To protect against this project being gone forever I'm forking it. I might do something with it, I might not, but at least it's preserved for at least my own usage.


<img src="https://image.flaticon.com/icons/svg/921/921691.svg?sanitize=true" width="200px">
<small>Icon made by Freepik from www.flaticon.com</small>

# What is this
This is a tool to make switch hacking easier.
It not groundbreaking, but it certainly isn't bad. This windows applications allows you to easily extract premade packages for the microsd card, which goes into the switch.
Also this tool has TegraRcmSmash by @rajkosto and the drivers included which allow you to launch payloads from your windows machine. Hopefully you find this program useful.

# How to use
Follow this image guide: https://imgur.com/a/zljwjZM

# Download
You can download either an installer (recommended) or a portable version(extract everything, else it won't work) 

[here](https://github.com/getraid/SHAIO/releases/latest)


# How to Compile 
<small><center>this part is for people who want to improve the code:</center></small>
Copy the contents of SHAIO/InternalFiles into SHAIO/SwitchHacksAllInOne/bin/debug and SHAIO/SwitchHacksAllInOne/bin/release folders and compile as usual via VisualStudio. All in written in C#.

# How to make my own version of this
Make sure to change the version and releases in SHAIO/docs/version.xml, as this is used by the updater.
If you want to change the folder structure: Every path is defined in PathSettings.cs

To make your own installer, download [InstallForge](https://installforge.net/download/) and open SHAIO/InstallForge PackageFile/Shaio.ifp. There you can adjust the settings you want and export as an installer. Make sure to set the proper version as well.

# Legal things
I don't want to be associated with piracy or some other sort of illegal activity.
The files and payload by Team Executer were only added because you can use the homebrew portions for free.
Everything else (like backup-loading) involves a licence, therefore I assume you only have good intentions and use the free/legal aspect of the homebrew portion of SX OS.

# Credits 
```
Special thanks to the people who made this possible:
------------------------------------------------------------ 
The Switchbrew-Team - http://switchbrew.org 
Michael/SciresM - https://twitter.com/SciresM 
naehrwert - https://twitter.com/naehrwert 
fail0verflow - https://twitter.com/fail0verflow 
DavidBuchanan314 - https://github.com/DavidBuchanan314 
ktemkin - https://www.ktemkin.com/ 
hedgeberg - https://twitter.com/hedgeberg 
rajkosto - https://github.com/rajkosto 
`... and many more that I forgot to mention (I'm sorry!) ⊙﹏⊙ 
------------------------------------------------ 
Other Stuff used: mahapps.metro MIT- https://mahapps.com/
Autoupdater.NET MIT- https://github.com/ravibpatel/AutoUpdater.NET
