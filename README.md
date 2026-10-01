# thE-noteTaker models

Pre-converted model weights used by [thE-noteTaker](https://github.com/ElijahQatana/thE-noteTaker)'s first-run model setup.

See the [latest release](../../releases/latest) for downloadable assets. Converted from NVIDIA's `parakeet-tdt-0.6b-v3` and `diar_streaming_sortformer_4spk-v2.1` NeMo checkpoints (both on HuggingFace) using [parakeet.cpp](https://github.com/Frikallo/parakeet.cpp)'s `convert_nemo.py`. This repo only redistributes the converted weights for direct use by the app; it does not modify the underlying model.

## Licenses

The weights keep their upstream licenses, and they aren't all the same one:

| Model | License |
|---|---|
| Parakeet TDT 0.6b v3 | CC-BY-4.0. Credit NVIDIA; the files here are converted and split |
| Sortformer 4spk v2.1 | NVIDIA Open Model License, **not** CC-BY. A copy is in [`LICENSES/`](LICENSES/) |
| Silero VAD v5 | MIT |

The attribution and change notes are in [`NOTICE`](NOTICE), and per-file detail is in [`LICENSES/README.md`](LICENSES/README.md). The MIT `LICENSE` at the top of this repository covers the repository's own files, not the weights.
