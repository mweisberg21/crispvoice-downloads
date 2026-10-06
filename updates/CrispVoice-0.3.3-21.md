<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# CrispVoice 0.3.3

- Added Apple text cleanup on supported Macs with Apple Intelligence.
- Added local Ollama cleanup with a downloaded model.
- Added optional Qwen 2B and 4B model downloads inside CrispVoice on Apple silicon.
- Kept speech recognition and text cleanup as separate choices.
- Added checks for file paths, formatted amounts, and code symbols in local output.
- Allowed local cleanup retry from a saved transcript when paid requests are off.
- Skipped unused cleanup model preparation in Transcript-only mode.

Local cleanup needs no API key or cleanup charge. A local failure does not switch to a cloud provider. Cloud speech can still add charges if selected. Existing cloud settings remain unchanged.

Apple and the downloaded 2B model have completed fixed text checks on one Mac. The 4B model and actual Ollama inference remain test options. Complex edits can retain the original draft wording. No accuracy or speed guarantee applies.

This update keeps the same app identifier and Developer ID certificate. Saved settings and provider keys stay on your Mac. Model files stay separate from app updates.
