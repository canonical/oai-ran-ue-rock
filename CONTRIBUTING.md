# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:oai-ran-ue_2.1.1_amd64.rock docker-daemon:oai-ran-ue:2.1.1
docker run -d oai-ran-ue:2.1.1
```
