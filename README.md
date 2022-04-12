# Demo workflows + inputs 


Please read more documentation at [https://docs.osmedeus.org/](https://docs.osmedeus.org/)

```shell

# running Jaeles and Nuclei scan on the list of ip
osmedeus scan -m vulnerability-scan.yaml -t inputs-host-with-port

# running ffuf with some filtered
osmedeus scan -m content-discovery.yaml -t inputs-urls

# doing portscan -> vulnscan -> dirbscan
osmedeus scan -f sample-workflow -t inputs-host-only
```


