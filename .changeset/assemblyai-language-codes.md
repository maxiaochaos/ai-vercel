---
'@ai-sdk/assemblyai': patch
---

Add a `languageCodes` transcription option for AssemblyAI code switching. It is sent as `language_codes`, and transcript responses that include `language_codes` or `language_detection_options` are exposed on provider metadata.
