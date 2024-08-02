# archive-docker

## build and push archive images
To build alt docker images for dates 20230615 and 20230515, for branches p10
and sisyphus, for arches amd64 and arm64, and push them to the
`registry.altlinux.org/obirvalger/archivei`, run:
```
./archive-docker.py \
    --date 20230615 20230515 \
    --registry registry.altlinux.org \
    --organization obirvalger \
    --name archive \
    --branch p10 sisyphus \
    --arch amd64 arm64 \
    --packages apt-repo
```
