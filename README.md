Minecraft Remote Controller
===========================

This is a super simple client application that can be used to communicate with a remote Minecraft server as long as Rcon protocol is enabled. Originally it was part of the [rconsharp](https://github.com/stefanodriussi/rconsharp), developed with the purpose of showing how to use the library but on a second thought, it just doesn't belong there, so now it has his own repository.

It's developed using WPF so technically it's Windows only (maybe i'll create another version more OS independent). As the name suggests, it's really straightforward: connects to a RCON Minecraft Server (but actually could be any RCON enabled server if you can stand the pixeled theme), sends commands and reads responses.

![Minecraft RCON Client screenshot](/assets/screenshot.png)

## F.A.Q.

  + Q: _How do I get this ?_

  A: You can clone this project and compile it with Visual Studio (you can download the [Express](http://www.visualstudio.com/downloads/download-visual-studio-vs#d-express-windows-desktop) version for free) OR you can go to the [Releases](https://github.com/stefanodriussi/minecraft-remote-controller/releases) section over here and get the latest packaged build.

  + Q: _Do I need something particular to run it ?_

  A: Yes, you do! Minecraft Remote Controller is built using [.net Framework 4.5](http://www.microsoft.com/en-US/download/details.aspx?id=30653) and thus you'll need it installed on your Windows machine. I'm totally sure it will work flawlessly on Windows 8/7/Vista but I didn't have the chanche to try it on Windows XP (but hey ... that OS is dead now ;) )

  + Q: _I've run it but it does nothing! Is it broken ?_
  
  A: Everything is possible but first try to click on the `settings` button on the upper right and enter your server address, port and password. Be sure your server has RCON enabled in the settings file.
