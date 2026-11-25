# AuthentiChain

Capture-only blockchain provenance demo (SHA-256 + DCT pHash, simulated on-chain registry).

- Static site, no build step. Deploy the folder as-is on Vercel (Framework Preset: Other).
- Must be served over HTTPS (camera needs a secure context). Vercel does this automatically.

## Demo flow
1. Register tab: open camera, capture. Tap "Save original photo".
2. Verify tab: choose the saved photo -> Exact match.
3. Edit the saved photo (resize / filter / WhatsApp it) and verify -> Perceptual match.
4. Verify any unrelated photo -> No provenance record.
