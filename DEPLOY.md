# Publish AIM/0 using GitHub Pages

The game is a static website. GitHub Pages can publish it from a public repository on GitHub Free, without a paid host or build step.

## 1. Create the repository

1. The public `asfva/AIM0` repository has been created.
2. The game and documentation are committed in the repository root.
3. Verify `index.html` is present in `main`.

## 2. Enable Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, then **Save**.
4. Once GitHub indicates that the deployment is live, open the site's **Visit site** link. Its URL will resemble `https://asfva.github.io/AIM0/`.

## 3. Test before posting on X

- Challenge and Practice both start and end correctly.
- Camera permission is requested only in webcam mode; pinch-to-fire works in Chrome on HTTPS.
- Camera indicator switches off when the round/session ends.
- **Save scorecard** downloads a PNG with the right score/accuracy/input mode and no camera image.
- **Post to X** opens a draft with an actual public Pages link (not `localhost`). Check the link before publishing.
- Check on your Mac and, if possible, one other computer. Webcam frame rate and pinch accuracy vary with hardware.

## 4. Final launch housekeeping

- Verify [Play AIM/0](https://asfva.github.io/AIM0/) opens after Pages is enabled.
- Optional: add your own GitHub username, X profile and launch demo video to the README.
- Choose a code license before describing the repository as open source.
- If you later change the repository name, the project Pages URL changes too.
- This version deliberately uses an X Web Intent: it can't attach an image to the X post automatically. Players must attach their downloaded scorecard.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site