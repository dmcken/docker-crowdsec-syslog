# Basic setup

This basic setup uses the built in crowdsec syslog handler.

Entering the container:

```bash
docker compose exec -it crowdsec bash
```

Adding the syslog raw parser:
cscli parsers install crowdsecurity/syslog-logs
cscli parsers install a1ad/mikrotik-logs

Setting your ID (to connect to your account):

```bash
cscli console enroll <your id>
```

Alternative commands:

```bash
cscli parsers list
cscli alerts list

```

Debugging:

```bash

cscli explain --type syslog --log "system,error,critical login failure for user david.mcken from 10.252.10.2 via winbox" client=172.20.255.254 type=syslog"
```
