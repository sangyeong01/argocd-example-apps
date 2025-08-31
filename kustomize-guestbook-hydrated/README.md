# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/sangyeong01/argocd-example-apps.git
# cd into the cloned directory
git checkout 484446c13f3409972133e39fa2d26d4fd5f592e4
kustomize build ./kustomize-guestbook
```
