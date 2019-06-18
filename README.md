![HTML5 Speedtest Logo](https://github.com/adolfintel/speedtest/blob/master/.logo/Readme-Logo.png?raw=true)



# This is a Docker Version for Linode 


# HTML5 Speedtest

No Flash, No Java, No Websocket, No Bullshit.

This is a very lightweight Speedtest implemented in Javascript, using XMLHttpRequest and Web Workers.

## Try it
[Take a Speedtest](http://speedtest.fdossena.com)

## Compatibility
Only modern browsers are supported (IE11, latest Edge, latest Chrome, latest Firefox, latest Safari)

## Features
* Download
* Upload
* Ping
* Jitter
* IP Address
* Telemetry (optional)
* Results sharing (optional)

![Screenshot](https://speedtest.fdossena.com/screenshot.png)

## How to use in your site
* See the examples
* [Read the wiki](https://github.com/adolfintel/speedtest/wiki)
* Read doc.md

## Docker + Docker Compose

The project includes a basic `docker-compose.yml` for development.  To run, execute the following:

```
$ docker-compose build

$ docker-compose up
```


Speedtest will be available at [http://0.0.0.0:8888/](http://0.0.0.0:8888/).  You can try out all of the examples via their associated urls (i.e. `http://0.0.0.0:8888/example1.html`).

To run via Docker directly:

```
$ docker build -t adolfintel/speedtest:latest .

$ docker run -d --name  speedtest -p 0.0.0.0:80:80 adolfintel/speedtest:latest
```

## Multiple test servers
Please see the ```mpot``` branch

## Node.js backend
A Node.js implementation is available in the ```node``` branch, maintained by [dunklesToast](https://github.com/dunklesToast).

## Donate
[![Donate with Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/fdossena/donate)  
[Donate with PayPal](https://www.paypal.me/sineisochronic)  
Send ETH at this address: ```0x8A5273d4e2618c4cff2C62d8EB731701FceEd8E3```

## License
Copyright (C) 2016-2019 Federico Dossena

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/lgpl>.

