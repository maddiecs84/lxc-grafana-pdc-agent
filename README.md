# lxc-grafana-pdc-agent

A Debian LXC image containing the [Grafana PDC Agent](https://github.com/grafana/pdc-agent).

## Configuration

Once running run login to your instance and run `/etc/grafana/configure-pdc.sh` to enter your Grafana PDC configuration.

Alternatively provide your configuration as arguments to the script.

```bash
/etc/grafana/configure-pdc.sh "TOKEN" "CLUSTER" "GRAFANA_ID"
```

## Why?

I run a Home Lab on Proxmox and my preference is to manage CTs rather than a VM or CT running Docker images (with something like Portainer).