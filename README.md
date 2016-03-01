+---------------------------------------------------------------+
|                         EPT emulator                          |
|      Concert Protocole, aka "Protocole Caisse" in french.     |
| © 2016 Libre Informatique [http://www.libre-informatique.fr/] |
+---------------------------------------------------------------+

Emulated EPT: iCT250, iWL220

The server side
================

Low-layer tests
----------------

Launch the physical-server.js script in the terminal:

```
$ node physical-server.js
```

Middle-layer tests
-------------------

Launch the logical-server.js scrip in the terminal

```
$ node logical-server.js
```

Within the logical server, you will be able to answer "0" (success) or "1" (error) at the ```stat``` prompt, to emulate a failed or a successfull payment.
