## Demo workflows + inputs 

Please read more documentation at [📖 https://docs.osmedeus.org/](https://docs.osmedeus.org/)

```shell

# running Jaeles and Nuclei scan on the list of ip
osmedeus scan -m vulnerability-scan.yaml -t inputs-host-with-port

# running ffuf with some filtered
osmedeus scan -m content-discovery.yaml -t inputs-urls

# doing portscan -> vulnscan -> dirbscan
osmedeus scan -f sample-workflow -t inputs-host-only
```

## 📚 [The Slide can be found here](https://docs.google.com/presentation/d/1Mu6JqzIpLiPbwXtPraFJRNBCAu5OXZn4SMIcl8hvMWI/edit?usp=sharing)

## 🎥 [The recorded video can be found here](https://youtu.be/ohi0fsLTesw)
