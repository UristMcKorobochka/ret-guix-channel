To make packages available to your system add this to =~/.config/guix/channels.scm= list of definitions and run =guix pull=
```
(channel
 (name 'ret)
 (url "https://github.com/UristMkKorobochka/ret-guix-channel.git")
 (introduction
  (make-channel-introduction
   "b6245ee51bc6898e3331d5a21a30893c4728e0b5"
   (openpgp-fingerprint
    "411D 5521 01A3 A27A F3CB  00E7 6F90 2932 A5EC 0480"))))
```
