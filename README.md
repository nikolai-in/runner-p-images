# Runner **P** images

This repository contains packer templates tweaked to be built in proxmox and still be somwhat compatible with actions for original github runner images.
I will primarily focus on adapting windows 22 template, but might do the rest later.

Some of the changes:

- [ ] Use `proxmox` as a builder instead of `azure`
- [ ] Remove cloud providers tools
- [ ] Remove UE and Unity
- [ ] Add gitea act runner

```perl
^    ^
 \__/ \
0   0
  U
```
