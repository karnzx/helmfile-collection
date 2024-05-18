# kube-ops-view

<https://codeberg.org/hjacobs/kube-ops-view>

By default, ingress is disabled. To access WebUI just use kubectl port-forward

1. `helfile apply -i` on desired namespace
2. `kubectl port-forward service/kube-ops-view 8080:80`
