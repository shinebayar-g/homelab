Kubernetes cluster provisioned by talos.dev

### Create

talosctl cluster create --workers 3 --controlplanes 3

### Destroy

talosctl cluster destroy
rm ~/.talos/config
rm ~/.kube/config
