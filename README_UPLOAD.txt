CALVILLO WEBSITE — READY TO UPLOAD

Upload the CONTENTS of this folder to your GitHub repository root.
Do not upload the folder itself unless your repo is configured that way.

Included changes:
- index.html renamed correctly from index(1).html
- i18n.js renamed correctly from i18n(1).js
- Fullscreen intro overlay added to index.html
- Video added at assets/intro/intro-video.mp4
- Final org-chart image added at assets/intro/org-chart.png
- style.css updated with intro overlay styles

Current behavior:
1. Visitor opens index.html.
2. Fullscreen intro video plays muted.
3. When video ends, org-chart image appears for 3 seconds.
4. Overlay fades out and the normal homepage is shown.

Notes:
- Browser autoplay normally requires muted video. This is why the video is muted.
- Existing site references to local files such as img/ricardo.jpg and nota.pdf / nota2.pdf / nota3.pdf are still present, but those files were not included in the uploaded base assets. Add them later if needed.
- Contact form still uses Formspree placeholder FORM_ID unless you replace it with your real Formspree endpoint.
