Minecraft Remote Controller
===========================

This is a super simple client application that can be used to communicate with a remote Minecraft server as long as Rcon protocol is enabled. Originally it was part of the [rconsharp](https://github.com/stefanodriussi/rconsharp), developed with the purpose of showing how to use the library but on a second thought, it just doesn't belong there, so now it has his own repository.

It's developed using WPF so technically it's Windows only (maybe i'll create another version more OS independent). As the name suggests, it's really straightforward: connects to a RCON Minecraft Server (but actually could be any RCON enabled server if you can stand the pixeled theme), sends commands and reads responses.

![Minecraft RCON Client screenshot](/assets/screenshot.png)
