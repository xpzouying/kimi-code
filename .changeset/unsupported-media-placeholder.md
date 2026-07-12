---
"@moonshot-ai/kosong": patch
"@moonshot-ai/kimi-code": patch
---

Reading an image or video in a format the model does not support (e.g. avif) no longer fails the request; it degrades to a placeholder so the session keeps working.
