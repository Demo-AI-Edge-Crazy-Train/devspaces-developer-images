# Developer Images with OpenCV included

Containers images with tools for developers 👨‍💻👩‍💻

## Developer Base Image

```sh
podman build -t quay.io/demo-ai-edge-crazy-train/base-developer-image:opencv --squash base/fedora
podman login quay.io
podman push quay.io/demo-ai-edge-crazy-train/base-developer-image:opencv
```

## Developer Universal Image

```sh
podman build -t quay.io/demo-ai-edge-crazy-train/universal-developer-image:opencv --squash universal/fedora
podman login quay.io
podman push quay.io/demo-ai-edge-crazy-train/universal-developer-image:opencv
```

# License

Che is open sourced under the Eclipse Public License 2.0.
