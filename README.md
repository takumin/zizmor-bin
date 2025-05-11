# zizmor-bin
Private static build of `zizmor`

# About release workflow
In this repository, we will generate binaries from the main branch and upload them to the release page.
When a new version is released, please set the release tag with the following command.

```console
# latest release tag
$ task release:latest
# versioned release tag
$ task release:version:v1.0.0
```
