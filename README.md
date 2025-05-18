# NETBIRD DOCKERLESS
## DOING
Making clean documentation
Making ansible playbook

## Why ?
I just didn't want to use docker for this one.

## How to use (ansible-playbook)?
```bash
```

## How to use (bash script)?
```bash
```

## Detailed reverse operations:
### Generate SSL certificates

### Install and configure Zitadel

### Install, configure and run netbirdio/dashboard

### Install, configure and run management, relay and signal

#### Management
go run . management --config /etc/netbird/management.json --port 4000 --log-file /tmp/oo.log --log-level debug --disable-anonymous-metrics --metrics-port 8888
#### Relay
go run . --log-level info -e 'rels://xxxx.xxxx.xxx' -l ':80' -s '' --metrics-port 9999
#### Signal
go run . run --port 10000 --log-level debug --log-file /tmp/ii.log

### Install, configure and run coturn

### Configure Nginx as a reverse proxy for all setup

### Profit !
