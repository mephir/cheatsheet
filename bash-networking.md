# Bash Networking

### Checking if port is opened
```bash
$ true &>/dev/null </dev/tcp/127.0.0.1/${port} && echo open || echo closed
```
