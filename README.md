# Jitsi + Jicofo + Jitsi-Videobridge + Prosody + Nginx

Jitsi is an audio/video and chat communicator that supports protocols such as SIP, XMPP/Jabber, AIM/ICQ, IRC and many other useful features.

[![Docker Build Status](https://img.shields.io/docker/build/sfoxdev/jitsi.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/automated/sfoxdev/jitsi.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/pulls/sfoxdev/jitsi.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/stars/sfoxdev/jitsi.svg?style=flat-square)]()

## Usage

`docker run -d -v /srv/ssl:/keys:ro -p 80:80 -p 443:443 -p 10010-10020:10010-10020 --name=jitsi sfoxdev/jitsi`
