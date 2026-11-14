# AIM/0 — launch kit

## 15-second screen recording

Keep your webcam preview visible in the game. Record a real run; no intro slides.

- **0–3s:** hand in frame, crosshair follows.
- **3–10s:** two clear pinch shots on moving targets with sound on.
- **10–13s:** one miss or adjustment, then a hit — genuine play is better than a perfect montage.
- **13–15s:** finish screen with scorecard. Overlay the live playable URL (after publishing).

Use a 16:9 capture with the game's UI legible. Avoid fake scores, stock animations and loud music.

## Suggested first X post (from the creator)

> I wanted to know how far a regular webcam could go as a game controller.
>
> So I built AIM/0 — a tiny browser shooting range. Move a finger to aim, pinch to shoot. No headset or controller.
>
> It runs right in the browser. [PLAY LINK]
>
> MediaPipe + vanilla JS. Here's what it looks like:

Attach the real 15-second clip. If it fits your voice, a brief follow-up can explain the hand-landmark math and why reliable gesture detection was harder than expected.

## Reply when someone shares a score

Avoid automatic engagement-bait replies. React to something specific: a particularly high accuracy, a funny miss, unusual camera setup, or feedback about pinch reliability. Use that feedback to improve the actual game.

## Later

A lightweight changelog, browser compatibility notes, and a second short technical clip are more useful than a flood of similar promotional posts.

## Player score-sharing post

When someone completes a webcam run, **Post to X** opens an editable draft like:

> Apparently a pinch makes a pretty decent trigger.
>
> I scored 2,951 points in AIM/0’s 30-second run with 94% accuracy.
>
> #CreativeCoding

The score and accuracy are generated from the player's actual run. Practice and mouse sessions get fitting alternatives. Once deployed over HTTPS, the public game link is appended automatically. Attach the downloaded scorecard separately if desired; the X web-intent API cannot upload the image.