# Socker SOCKS5 server

From little things big things grow?

Have intentions to turn this into an alternative to chisel which is often flagged by malware scanners.

At this point it just serves a SOCKS5 proxy with optional authentication with the intention of being reverse
port forwarded over an SSH connection

i.e. 

```
ssh user@host -R 1080:127.0.0.1:1080
```

All credits for go-socks5 module used here goto thinkgos for his fork and the original author armon, all I have done is make it into a command line tool.

_Note: I am just learning golang so dont flame me for trying._