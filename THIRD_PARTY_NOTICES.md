# Third-Party Notices

ZeroCross includes or uses the following third-party software and media. Each
item remains subject to its own license. The generated release file
`THIRD_PARTY_BUNDLED_LICENSES.md` contains the license texts detected in the
bundled JavaScript dependencies.

## MP3 encoder

- `@breezystack/lamejs` 1.2.7 — GNU Lesser General Public License v3.0
- Package source: <https://github.com/shijinyu/lamejs>
- Original project: <https://github.com/zhuker/lamejs>
- License: <https://www.gnu.org/licenses/lgpl-3.0.html>

The release build identifies this dependency in a separate `lamejs-lgpl`
JavaScript chunk and links back to this notice. ZeroCross does not claim
copyright over this library.

## Plate Reverb impulse response

ZeroCross includes `EMT 140 Medium 5`, created by Greg Hopkins
(`recordinghopkins`).

- Original pack: <https://freesound.org/people/recordinghopkins/packs/11031/>
- Source mirror: <https://oramics.github.io/sampled/IR/EMT140-Plate/>
- License: Creative Commons Attribution 4.0 International
  (<https://creativecommons.org/licenses/by/4.0/>)
- Changes made for ZeroCross: converted from 24-bit to 16-bit PCM and added a
  20 ms endpoint fade; not normalized, resampled, stretched, or truncated.

## Other bundled dependencies

- `@zip.js/zip.js` 2.8.34 — BSD 3-Clause License
- `lucide-react` 1.22.0 — ISC License; included Feather-derived icons retain
  their MIT notice
- `pretendard` 1.3.9 — SIL Open Font License 1.1
- `react` 19.2.7 — MIT License
- `react-dom` 19.2.7 — MIT License
- `scheduler` 0.27.0 — MIT License

Version-specific license texts included by the build are authoritative for the
exact files in a release. This notice is informational and is not legal advice.
