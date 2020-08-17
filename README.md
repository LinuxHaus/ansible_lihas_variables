# ansible-lihas-ansible
Create variable trees in namespaces to be able to 'merge' variables from different sources like multiple group_vars and host_vars.

Typical host_vars or group_vars look like this:
```
# cat samplehost.yml
samplehost:
  config:
    searchnames: xy
# cat samplegroup.yml
samplegroup:
  config:
    searchnames: xyz
```
