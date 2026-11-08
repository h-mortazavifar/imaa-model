# Imaa reply model

The on-device reply-suggestion model used by [Imaa](https://cafebazaar.ir/app/com.peyvand.imaa), an SMS app for Android.

This repository holds **only the model file**, as a release asset, so the app can download it when the user asks for it in Settings. Inference runs entirely on the phone; nothing is sent anywhere.

- **File:** `gemma3-1b-it-int4.litertlm` (Gemma 3 1B instruction-tuned, int4, LiteRT-LM format), 584 MB
- **Download:** [Releases → gemma3-1b-it-int4](../../releases/tag/gemma3-1b-it-int4)

## Licence

Gemma is provided under and subject to the Gemma Terms of Use found at <https://ai.google.dev/gemma/terms>. See [NOTICE](NOTICE). Use of the model is also subject to the Gemma Prohibited Use Policy: <https://ai.google.dev/gemma/prohibited_use_policy>.
