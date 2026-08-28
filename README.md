# Camera Operator

Official project page for **Camera Operator: Object-Grounded Camera Trajectory
Generation from Text and 3D Bounding Box Sequences**, accepted at ACM
Multimedia 2026.

- [Project page](https://huzhongyyuan.github.io/CameraOperator/)
- [Camera-ready paper](https://huzhongyyuan.github.io/CameraOperator/assets/camera-operator-mm26.pdf)
- DOI: [`10.1145/3767308.3835459`](https://doi.org/10.1145/3767308.3835459) (activation pending)

Language specifies sequence-level camera-motion intent, while dynamic 3D
target boxes provide frame-wise geometric grounding. Camera Operator generates
an object-grounded 6-DoF camera trajectory; it does not itself generate RGB
video.

## Artifact status

The project page and camera-ready article are available. Training code, model
weights, and BlockCam downloads are not public yet. Their links will be enabled
only after the corresponding packages and release terms are ready.

See [`RELEASE_STATUS.md`](RELEASE_STATUS.md) and
[`ASSET_NOTICES.md`](ASSET_NOTICES.md) for the current public boundary and
figure provenance.

## Citation

```bibtex
@inproceedings{hu2026cameraoperator,
  author    = {Hu, Zhongyuan and Ma, Yue and Wang, Jiangming and Li, Ronghui and Li, Xiu},
  title     = {Camera Operator: Object-Grounded Camera Trajectory Generation from Text and 3D Bounding Box Sequences},
  booktitle = {Proceedings of the 34th ACM International Conference on Multimedia},
  year      = {2026},
  doi       = {10.1145/3767308.3835459}
}
```
