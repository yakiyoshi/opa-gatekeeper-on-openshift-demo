# opa-gatekeeper-on-openshift-demo

## How to deploy OPA Gatekeeper on OpenShift

```
$ oc apply -f https://raw.githubusercontent.com/open-policy-agent/gatekeeper/release-3.7/deploy/gatekeeper.yaml
$ oc adm policy add-scc-to-user privileged -z gatekeeper-admin
```
