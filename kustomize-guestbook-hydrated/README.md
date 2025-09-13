# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sangyeong01/argocd-example-apps.git
# cd into the cloned directory
git checkout 1a20135fc634985c237067869bc7471b581f83f3
kustomize edit set namesuffix -- -hydrated
kustomize build ./kustomize-guestbook
```
