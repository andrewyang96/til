---
title: SSH With Port Forwarding
category: unix
---

Use the `-L` flag with `ssh` to forward a connection to a remote server

```
$ ssh someserver -L3000:localhost:3000
```
