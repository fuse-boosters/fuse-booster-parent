
## Openshift Developer Sandbox

https://developers.redhat.com/developer-sandbox/get-started

* Get command line tools from About

```
oc login --token=sha256~FOas... --server=https://api.sandbox...openshiftapps.com:6443
odo login --token=sha256~FOas... https://api.sandbox...openshiftapps.com:6443
```

## Deploying DevFile with ODO

```
mkdir myproj; cd myproj
odo create java-maven --starter
odo url create
odo push
```

## Local Cluster with Red Hat CodeReady Containers

https://cloud.redhat.com/openshift/create/local

```
MacBookPro: (13-inch, 2019, Four Thunderbolt 3 ports)
Processor:  2,4 GHz Quad-Core Intel Core i5
Memory:     16 GB 2133 MHz LPDDR3
```

* Consumes too much system resources even when idle.
