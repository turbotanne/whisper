## SONA8 Whisper Notes

- Baseline models: `small.en`, `medium`, `large-v3`
- Target metrics: < 8% WER on mixed German/English meetings (45 min)
- Required outputs:
  - JSON transcripts w/ timestamps
  - Markdown meeting summaries (<= 250 words)
- Next steps:
  1. Wire diarization to pyannote 3.1
  2. Benchmark GPU vs CPU inference on RTX 4090 & M3 Max
  3. Add guardrails for overlapping speakers