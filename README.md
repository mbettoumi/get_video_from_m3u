get\_video\_from\_m3u
=====================

This script downloads MPEG-TS chunks as referred by a given m3u playlist
into a local file. Use this if you want to watch a streamed video on
another device or if you want to buffer it as a whole at maximum quality,
even though your internet connection sucks.

Usage
-----

Start video playback in a browser (e.g. Chrome), open the developer tools,
search the network tab for an .m3u or .m3u8 URL, right-click -> copy as cURL,
start this script and paste what you copied.

Dependencies
------------

 * [Python](https://www.python.org/)
 * [Requests: HTTP for Humans](http://docs.python-requests.org/en/latest/)
 * [DBus-Python](https://pypi.python.org/pypi/dbus-python/)
 * [KDE](https://www.kde.org/) (for kdialog)