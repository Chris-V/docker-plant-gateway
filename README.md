# Plant-gateway docker image

This is a basic docker image for https://github.com/ChristianKuehnel/plantgateway.

## Command

```bash
docker run -d --net host -e TZ=America/Toronto -v $(PWD)/plantgateway-config:/config ghcr.io/Chris-V/plantgateway
```

On a first run, a sample plantgw.yaml file will be added to your config volume. Change that to your liking and restart the container.

