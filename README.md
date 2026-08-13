# Lumba — website

Static site for the Lumba iOS app (posture & back pain).
Served with GitHub Pages from the `main` branch, root folder.

| Page | Purpose |
|---|---|
| `index.html` | Marketing page |
| `privacy-policy.html` | Privacy Policy — linked from the App Store listing and from inside the app |
| `terms.html` | Terms of Use — required next to any auto-renewing subscription |
| `support.html` | Support URL — required by App Store Connect |

The privacy policy describes the app's actual data flow: the posture photo is
analysed on-device with Vision and never uploaded; only an anonymous ID and the
subscription status reach Firebase.
