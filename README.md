# Pajaro

## Installing

### Metallb

    $ k create ns metallb-system
    $ k apply -f manifests/metallb.yaml
    $ k apply -f manifests/metallb_crd.yaml

### Prometheus

    $ k create ns monitoring
    $ k apply -f manifests/prometheus.yaml

### PiHole

    $ k create ns pihole-system
    $ k apply -f manifests/pihole.yaml
