# Krew asdf Plugin

This is the plugin repo for [asdf-vm/asdf](https://github.com/asdf-vm/asdf.git)
to manage [kubernetes/krew](https://krew.sigs.k8s.io/).

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add krew https://github.com/josephlim75/asdf-krew.git
asdf list-all krew
asdf install krew 0.4.2
asdf global krew 0.4.2
krew version
kubectl krew version
`````