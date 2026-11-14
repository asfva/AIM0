# AIM/0 — Privacy notes

AIM/0 is a small browser experiment, not an account-based service.

- **Camera:** disabled until you choose webcam mode and grant browser permission. MediaPipe processes camera frames within your browser. This app does not record video, upload webcam frames, or deliberately transmit player images.
- **Stopping:** camera tracks are stopped when a round/session ends or the page is left. When the webcam session's tab is hidden, the run ends and tracks are stopped.
- **Scores:** maintained in memory for a run; not stored on a server. Scorecard PNGs are generated on your device only when you click Save.
- **Sharing:** Post on X opens an editable draft containing the score stats and (on the hosted site) a link to the game. X is a separate service with its own policies. Scorecard images are not automatically attached or uploaded.
- **Third parties:** the game fetches MediaPipe JavaScript/WASM from jsDelivr, a hand-tracking model from Google Cloud Storage, and optional fonts from Google Fonts. Requests to these services reveal normal connection information such as IP address. MediaPipe's published privacy notice also describes collection of performance/utilization metrics. We have not independently audited those third-party services.
- **Hosting:** GitHub Pages may log visitor IP addresses for security. See GitHub's privacy documentation.

This describes the included client-side code. Review the live hosting and dependency configuration before making new privacy guarantees.