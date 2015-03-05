# telnet-element
A websocket telnet emulator. Supports utf-8 and windows-1252/cp-437 encoding.

This requires a websocket/TCP relay, due to browser limitations around opening TCP sockets. Here are a couple relays you can set up:<br>
* python - websockify.py - https://github.com/kanaka/websockify
* nodejs - node-tcp-ws-router - https://github.com/bioid/node-tcp-ws-router

Uses a modified and browserified version of echicken's ansi-graphics module to parse the ansi escape codes. Original found here: https://github.com/echicken/node-ansi
