# volatility-5.4.0-4-amd64-profile
Le profile volatility correspondant à Debian 11 (Bullseye) avec le kernel 5.4.0-4-amd64

Si un jour vous avez un dump de RAM à analyser et que celui-ci provient d'un machine tournant sous Debian avec le kernel 5.4.0-4-amd64 (pour une épreuve de FCSC par exemple 😉).

```
$ uname -a
Linux debian 5.4.0-4-amd64 #1 SMP Debian 5.4.19-1 (2020-02-13) x86_64 GNU/Linux
$ cat /etc/debian_version
bullseye/sid
```

## Installation (pour Linux)

Après avoir installé [volatility](https://www.volatilityfoundation.org/), il faut placer le fichier [Debian-5.4.0-4-amd64.zip](Debian-5.4.0-4-amd64.zip) dans le répertoire `/usr/local/lib/python2.7/dist-packages/volatility-2.6.1-py2.7.egg/volatility/plugins/overlays/linux/`.
