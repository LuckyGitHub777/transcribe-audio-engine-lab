# Transcribe Audio — Engine Lab

**Explore online:** [Open the public browser experience](https://luckygithub777.github.io/transcribe-audio-engine-lab/). The website explains transcription pipeline concepts; actual audio transcription requires the separately installed source tools.

A small Python learning lab for inspecting audio transcription engine integration, GPU/CPU selection, model readiness, and safe transcript-file creation. The bundled tests use **synthetic mock engines**, not personal recordings or online inference.

## Test without downloads

```bash
python tests/test_engine_mock.py
python tests/test_probe_mock.py
```

Actual transcription requires separately installed PyTorch, Whisper and compatible model files, plus media that you are authorized to process. Models may be downloaded on first use; review dependencies and privacy implications before using real recordings. This source edition does not include an installer, a hosted service, model weights, or recordings.

**License:** The original MIT [LICENSE](LICENSE) and attribution are preserved. Automated transcripts may contain mistakes; verify important facts against source media. [MANIFEST.sha256](MANIFEST.sha256) records source hashes.
