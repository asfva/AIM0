# AIM/0 — The Touchless Range

**A tiny target range you can play with a webcam.** Move your index finger to aim, pinch your thumb and index finger to fire. Or try it with a mouse.

**[Play AIM/0](https://asfva.github.io/AIM0/)** · [Source code](index.html) · [How it works](#how-it-works) · [Privacy](#privacy)

## The game

- **30-second challenge:** score as many hits as you can before the timer runs out.
- **Free practice:** no clock, no ammo limit.
- **Webcam:** point with your index finger; pinch to shoot, release to reset.
- **Mouse:** move to aim, click to fire.
- **Results:** save a 1200 × 675 scorecard PNG and open a draft post on X with your actual stats. Add the PNG to the post manually.

No login, accounts, online scoreboard, or game server.

## How it works

AIM/0 uses **MediaPipe Hand Landmarker** for real-time, one-hand tracking in the browser. The rest is vanilla JavaScript, Canvas 2D, and Web Audio. The scoring and target movement happen client-side. There is no framework or build step.

**Requirements:** recent Chrome or Edge, camera permission for webcam mode, and HTTPS (or localhost) for camera access. External model files and fonts require an internet connection. Mouse mode works without a camera.


## Privacy

Webcam mode is optional. The app requests camera permission when you select webcam play, processes frames in the browser, does not record or upload footage, and stops camera tracks at the end of a session or when the page is hidden. Scorecards contain **stats and graphics only**, never camera images. Third-party services supply the MediaPipe library/model and optional fonts; those providers may receive standard web requests and MediaPipe may collect performance/usage metrics. Read more in [PRIVACY.md](PRIVACY.md).

## Share a run

1. Complete a challenge or end free practice.
2. Choose **Save scorecard** to get a downloadable PNG.
3. Choose **Post to X** to open a draft with the run stats and playable link.
4. Attach the saved PNG yourself if you'd like an image in the post.

The X draft is editable. The game never publishes on anyone's behalf.

## Open source

AIM/0 is released under the [MIT License](LICENSE). Contributions, experiments and feedback are welcome.
