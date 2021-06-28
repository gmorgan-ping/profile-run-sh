# profile-run-sh

To deploy this example in your K8s cluster, run the following Helm commands

```sh
helm \
    upgrade --install \
    <release-name> \
    pingidentity/ping-devops \
    -f https://raw.githubusercontent.com/gmorgan-ping/profile-run-sh/master/values.pf
```
