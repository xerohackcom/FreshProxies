<h1 align="center">
	<br>
	<img src="https://raw.githubusercontent.com/ProHackTech/FreshProxies/master/git_assets/logo.png" alt="FreshProxy Logo">
	<br>
	FreshProxy
</h1>

Python script to grab HTTP, HTTPS, SOCKS4 and SOCKS5 proxies fast.

## Instructions

You need the following python packages installed:

- argparse

- selenium

You will need Firefox installed on the system

## Features

[+] Grab Proxies

[+] Open proxied Firefox instances for each proxy in list


## How To

### Video Demonstration

*Grabbing Proxies*

<h3 align="center">
	<a href="https://www.youtube.com/watch?v=PlC5wXNXg1A" target="_blank">
		<img src="http://img.youtube.com/vi/PlC5wXNXg1A/0.jpg" alt="FreshProxy Demo" width="480" height="360" border="10" />
	</a>
</h3>

### HTTP Proxy

> python fp.py --type http

### HTTPS Proxy

> python fp.py -t https

### SOCKS4 Proxy

> python fp.py -t socks4

### SOCKS5 Proxy

> python fp.py -t socks5

### ALL Proxies

**NOTE**: This option gives error with http proxy grabbing, but all others are grabbed. Run this and then grab http proxy using "--type http" manually.

> python fp.py -t all

## Proxify Browser

This option allows you to open multi-threaded instances of Firefox run through proxies in the proxy list.

### Arguments available to use

*-pb* : proxy browser

*-ts* : timesec to run the browser sessions

*-f* : specify the proxy file list

Options '-ts' and '-f' optional.

### Proxify using default list

Uses default proxy list with name "proxies.txt" and timesec "9999"

> python fp.py -pb

### Proxify using custom list

> python fp.py -pb -f your_proxy_list.txt

### Proxify using custom list and timesec (for quick automation for stuff like view bots)

> python fp.py -pb -f proxies.txt -ts 120

### Proxify with timesec and default proxy list

> python fp.py -pb -ts 120


## License

```

MIT License

Copyright (c) 2019 prohack.tech

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

