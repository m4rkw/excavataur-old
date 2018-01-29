# Excavataur by m4rkw

Excavataur is a shim that provides a basic Excavator-style JSON api for cli
crypto mining tools so that they can be plugged into Minotaur.

See: https://github.com/m4rkw/minotaur

Currently supports:

 - ccminer (tpruvot variant) - https://github.com/tpruvot/ccminer.git
 - ccminer2 (alexis78 variant) - https://github.com/alexis78/ccminer.git
 - xmrig-nvidia - https://github.com/xmrig/xmrig-nvidia.git

It's very simple for me to add any CLI miner to this shim so if you would
like a particular miner added please raise an issue and I'll get to it.

Excavataur is primarily designed for use with Minotaur:

See: https://github.com/m4rkw/minotaur

## Usage

1. Edit excavataur.conf.example as: /etc/excavataur.conf

2. Run:

````
$ ./excavataur
````

Credits

- Much thanks to @gordan.bobic for packaging and invaluable input into the
  development of this tool
