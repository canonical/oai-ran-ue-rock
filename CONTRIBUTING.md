# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:oai-ran-ue_2.3.0_amd64.rock docker-daemon:oai-ran-ue:2.3.0
docker run -d oai-ran-ue:2.3.0
```
