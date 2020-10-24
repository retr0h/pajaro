# Pajaro

## Installing

Create namespaces

    $ k create ns pihole
    $ k create ns monitoring

Drop in the the manifests

    $ cp manifests/*.yaml /var/lib/rancher/k3s/server/manifests
