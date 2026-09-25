# Sleep Tracker v4 · Impeccable visual pass

Static mobile-first PWA for personal sleep tracking.

## What changed in v3
- Keeps Home / Log / Settings navigation.
- Adds brief "Why log this?" explanations inside the sleep log.
- Adds an optional CBT-I-inspired Sleep Thoughts reflection inside each log.
- Adds optional sleep-hygiene check-in items without turning them into a perfection score.
- Adds evidence-based Sleep Guide cards referencing AASM and NIH/NHLBI.
- Suggested bedtime is withheld until the configured number of logs (default 5) is available.
- Existing localStorage data key remains `sleepTrackerDataV1`, so prior sleep logs stay compatible.

## Notes
- Data remains on the device in localStorage unless exported manually.
- The suggested bedtime is a tracking estimate, not a medical prescription.
- Sleep restriction therapy is described educationally and should be individualized with safety in mind.


## v4 visual pass
- Impeccable-led mobile polish with stronger hierarchy, night-to-morning palette, refined forms, and 3-tab app navigation.
- No data model changes; existing localStorage records remain compatible.


## v4.1
- Added edit and delete controls for recent sleep logs.
- Editing restores all saved fields, including sleep hygiene and optional Sleep Thoughts.
- Added bilingual delete confirmation.
- Fixed Korean text leaking into English mode in CBT thinking-pattern options and placeholders.
- Language selector and quick language toggle now remain clean in English mode.
