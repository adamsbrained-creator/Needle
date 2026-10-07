# Needle

A personal, offline-first Android music player with its own look.
Built on top of [Rhythm](https://github.com/cromaguy/Rhythm) by Anjishnu Nandi, used under the GPL-3.0 license.

## How this repo works
- `needle-src.zip` holds the whole app source (every file keeps its original copyright notices).
- `.github/workflows/android.yml` unpacks it and builds the APK on every push.
- To update Needle: upload a new `needle-src.zip` (same name replaces the old one). The build starts by itself.
- The APK appears in the run's Artifacts (Actions tab).

## License
GPL-3.0, see `LICENSE`. See `NOTICE.md` for the attribution to the original project.
