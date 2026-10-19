# H3 Learning Writer 0.2.0-learning.1

Independent local fork of H3 Prompt Writer Standalone 0.1.9.

- Single generation and refinement history, with exact system-message snapshots.
- Result-video upload attached to a specific generation; editable actual used prompt.
- Eight timestamped frames, retained input references, asynchronous streamed API review.
- Automatically proposed supplemental system instructions scoped by writing model/mode.
- A second model text-review gate, version history, rollback, reset and disable controls.
- SQLite persistence, memory-only existing API credentials, temporary upload cleanup.
- No model-weight training, video regeneration benchmark, audio evaluation or Sequence integration.

Run `start.bat`, reconnect the Custom RunPod API with image input enabled, then open
the Learning Center button in the top toolbar. Existing original provider settings
and upstream source remain in place. Personal runtime data is excluded from the repository.

Changes in this independent version:

- English Learning Center in the top toolbar without covering Generate prompt.
- Anatomy and naturalness findings with timestamps and confidence.
- Automatically generated, copyable technical Refine instructions.
- Reversible list cleanup with active-version protection.
- Robust JSON escape handling and one bounded format-repair attempt.
- Safe error codes and analysis-stage reporting without exposing credentials.
- Compact instruction validation that avoids repeating full guides and media manifests.
- Completed video reviews remain saved if subsequent instruction validation fails.

Validation: 16 local tests pass. Live behavior depends on the connected model and
server configuration; automatic improvement in video quality is not guaranteed.

- Strengthen I2VA face, clothing and accessory fidelity, while respecting explicitly requested changes.
- Add structured reference-fidelity findings and a regression test; 17 tests pass locally.
