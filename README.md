# QRStream privacy policy

The published privacy policy for the two QRStream apps:

- **Android** — Google Play, `com.padovanl.qrstream`
- **Windows** — Microsoft Store, `SenseiPado.QRStream` (Store ID `9NSZTBS2QVJM`)

This repository exists only to serve that one page over GitHub Pages. Both
store listings need a publicly reachable privacy policy URL, and the app's own
repository is private, so Pages cannot serve it from there.

## The source of truth is not here

`docs/index.html` is a **copy** of `docs/privacy.html` in the (private) AirGapQR
repository. Edit it there, then copy it across:

```bash
cp ../AirGapQR/docs/privacy.html docs/index.html
git commit -am "Sync privacy policy"
git push
```

Letting the two drift would put a stale policy in front of users while the
repository says something else - the same class of mistake that had the Play
listing rejected in October 2026 for an icon that no longer matched the app.

## Publishing

Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/docs`.
The page is then at `https://<user>.github.io/qrstream-privacy/`.
