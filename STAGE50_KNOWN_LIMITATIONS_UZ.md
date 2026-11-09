# Stage 50 — Known Limitations & Honest Acceptance Status

1. Chromium E2E: `BLOCKED_BY_ENVIRONMENT`; localhost navigation blocked before page load. No browser assertion was executed.
2. Samsung Galaxy A14 physical testing: pending.
3. Local-first storage, no cloud sync, no app-side at-rest encryption.
4. JSON progress backup excludes IndexedDB audio blobs.
5. Web Speech API support/network varies by browser; no server-side transcription service.
6. External media/captions/embeds depend on provider and internet.
7. 15 MB-class app data payload remains; no Lighthouse/PageSpeed score claimed.
8. No generative AI backend and no official IELTS examiner score.
9. No official IELTS band conversion; 0–10 platform quality scores are internal learning indicators.
10. Deploy target file says repository `unbelievable-8-`; a previous conversation mentioned `Ielts-gooo`. Check the actual repository before upload. Manifest and Service Worker are project-relative, so the release is designed to work under a GitHub Pages project subpath after the repository target is confirmed.
