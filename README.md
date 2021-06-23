
## OpenShift Developer Sandbox

* Connect to the [OpenShift Developer Sandbox](https://developers.redhat.com/developer-sandbox/get-started)
* Get the command line tools from About
* Login to your Developer Sandbox

```
SANDBOX_URL="https://api.sandbox-m2.ll9k.p1.openshiftapps.com:6443"
AUTH_TOKEN="sha256~axy_GWIJNRFoJGfudPaRQT6xcT6QpK2wm6zelLHKO9A"
oc login --token=$AUTH_TOKEN --server=$SANDBOX_URL
odo login --token=$AUTH_TOKEN $SANDBOX_URL
```

## Deploying DevFile with ODO

Pick a Fuse Booster from [fuse-boosters](https://github.com/fuse-boosters?q=fuse-booster) and push it to OpenShift like this ...

```
git clone https://github.com/fuse-boosters/fuse-booster-camel-reset-openapi \
   && cd fuse-booster-camel-reset-openapi
   
odo push
```

Find more information at https://github.com/openshift/odo
