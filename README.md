# input-overlay
Please follow the install guide closely before asking questions about the installation.
Always download the latest release and NOT the sourcecode!
### [Install guide](https://vimeo.com/229296849)
#### On windows there's a chance that you'll need to install [Visual C++ 2015 Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=52685) because the plugin won't load otherwise

![logo](http://hnng.moe/f/WHZ)
Show keyboard, mouse and gamepad input on stream.
Available for OBS Studio 19.0.3+ on windows (32bit/64bit) and linux (64bit).
Does NOT work with OBS Streamlabs!
Head over to [releases](https://github.com/univrsal/input-overlay/releases) for binaries.

[Layout presets](https://github.com/univrsal/input-overlay/tree/master/presets)

### How to use
![tut](http://hnng.moe/f/WHe)
![tut2](http://hnng.moe/f/Xcp)

## Credits
input-overlay depends on [libuiohook](https://github.com/kwhat/libuiohook) by [kwhat](https://github.com/kwhat) licensed under the [GNU General Public Licence v3.0](https://www.gnu.org/licenses/gpl-3.0.txt)

More Information:
- [OBS resource page](https://obsproject.com/forum/resources/input-overlay.552/)
- [*.psd and fonts used](https://goo.gl/kyyoXx)
- [Making your own presets](https://vimeo.com/238275966)

Compiling:
Compiled against XInput9_1_0.lib instad of XInput.lib (Because the first one is avaiable
on Windows 7).
I compile the plugin with Visual Studio 2015 and static linking. If you need help with
setting up a development environment you might want to take a look at a tutorial I wrote
over at my [blog](https://universallp.wordpress.com/2017/08/17/obs-studio/).
To enable static linking in VS do the following:
```
Right-click the project "input-overlay" in VS > Properties > Configuration Properties
> C/C++ > Code Generation
Choose /MT for runtime library in the Release Configuration 
```
### Made a preset? Let me know and I'll add it to the repository!


https://web.archive.org/web/20200809061514/https://universallp.wordpress.com/category/allgemein/code/
