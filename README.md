# scribe-models

Unmodified copies of third-party open models, redistributed under their
licenses so that an installer can fetch them without an account or token.
This repository contains **no** application code.

Download them from the [Releases](../../releases) page; each release lists
SHA-256 checksums in `SHA256SUMS.txt`.

## Contents and attribution

| Archive | Original | Upstream revision | License |
|---|---|---|---|
| `pyannote--speaker-diarization-community-1.zip` | [pyannote/speaker-diarization-community-1](https://huggingface.co/pyannote/speaker-diarization-community-1) | `3533c8cf8e369892e6b79ff1bf80f7b0286a54ee` | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| `pyannote--segmentation-3.0.zip` | [pyannote/segmentation-3.0](https://huggingface.co/pyannote/segmentation-3.0) | `e66f3d3b9eb0873085418a7b813d3b369bf160bb` | MIT ([text](licenses/MIT-pyannote-segmentation-3.0.txt)) |
| `pyannote--wespeaker-voxceleb-resnet34-LM.zip` | [pyannote/wespeaker-voxceleb-resnet34-LM](https://huggingface.co/pyannote/wespeaker-voxceleb-resnet34-LM) | `837717ddb9ff5507820346191109dc79c958d614` | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

**pyannote.audio** models by Hervé Bredin and the pyannote contributors,
CNRS — <https://github.com/pyannote/pyannote-audio>. The speaker-embedding
model is a pyannote packaging of a [WeSpeaker](https://github.com/wenet-e2e/wespeaker)
ResNet34 model trained on [VoxCeleb](https://mm.kaist.ac.kr/datasets/voxceleb/)
(Chung, Nagrani, Zisserman), whose license it follows.

Each archive holds the files exactly as published upstream at the revision
above (only the repository's `.gitattributes` is left out), including the
original model cards (`README.md`) with their full citations and license
statements. **No changes were made** to any model.

If you use these models, please cite the works listed in their model cards
and support the authors at the original repositories.
