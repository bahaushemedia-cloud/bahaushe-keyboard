# BAHAUSHE Keyboard

A Keyman keyboard for the BAHAUSHE script (custom Hausa writing system).

## Install on Android (no PC needed)

1. Go to the [**Releases**](../../releases) tab of this repository
2. Download `bahaushe.kmp`
3. Install **Keyman for Android** from Google Play
4. Open the `.kmp` file on your phone — Keyman installs it automatically
5. Go to Keyman settings → enable BAHAUSHE keyboard

## How typing works

### Consonants (main layer)
| Key | Outputs |
|-----|---------|
| h | h glyph |
| s | s glyph (long press → sh) |
| k | k glyph (long press → ky, kw) |
| g | g glyph (long press → gy, gw) |
| ƙ | ƙ glyph (long press → ƙy, ƙw) |
| f | f glyph (long press → fy) |
| h | h glyph (long press → hw) |
| c | c glyph (long press → ct) |
| t | t glyph (long press → ts) |

All other consonants (d, b, ɓ, r, j, ɗ, n, z, y, l, w, ƴ, m) are single keys.

### Vowels (tap **Vowels** button to switch)
Short: a u o i e  
Long: ā ū ō ī ē

## Files
- `bahaushe.kmn` — keyboard source rules
- `bahaushe.keyman-touch-layout` — Android touch layout (phone + tablet)
- `bahaushe.kps` — package source
- `BAHAUSHE.otf` — font file
- `.github/workflows/build.yml` — auto-compile workflow
