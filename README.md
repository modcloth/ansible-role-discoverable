# ModCloth Discoverable

For implementing the client component of service discovery

## Variables

```yaml
#string, default: "* * * * *" - cron schedule for the node registration job
discoverable_cron_schedule: "* * * * *"

#string, required - the port on which the service is running
discoverable_discovery_port:

#int, required - the length of time a service's entry remains in etcd (recommended: 604800)
discoverable_discovery_ttl: 604800

#string, required - should be of the format "/%s"
discoverable_discovery_url: #example: /app-prod

#string, required
discoverable_etc_host:

#string, required
discoverable_etc_prefix: #example: /_discovery
```
## License

MIT.  See the [LICENSE](LICENSE) file for details
