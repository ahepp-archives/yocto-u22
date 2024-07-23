```
$ podman build . -t yocto-u22
$ podman run --userns=keep-id --rm -it -v $(pwd):/ws -w /ws yocto-u22
# . layers/poky/oe-init-build-env
# bitbake quilt-native
```
