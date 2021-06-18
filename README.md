# cursesGecko
A basic curses cryptocurrency tracker made for a college project.

![xfce4-term](https://imgur.com/4JSip73.png "Main screen on XFCE4 Terminal")

![xfce4-term2](https://imgur.com/HywaMPC.png "Alt screen on XFCE4 Terminal")

![vt100](https://i.imgur.com/lk5TA1s.png "Main screen on an emulated VT100")

Configuration is written in file __~/.cursesGecko/config.ini__ which is used to read the cryptos to track.
Default can be written in program itself.

The program is a Python script so it is run as _./cursesGecko_

Issues:
1. Pagination
2. Refresh is buggy. Might just be the Python module's problem
3. Graph is made using a simple normalize algo, have no idea if this is valid for such graphs. Further the idea is to represent trends.

