# CoreUI

The reader of the asset catalogues of the Mac (`.car`: colours, window buttons, symbols, icons) and the tools around it.  The big catalogues are fetched from a Mac, not stored here.

## catalogs/
The asset catalogues of the Mac that were extracted for the reader and the themes (one folder per framework or app: `AppKit`, `SystemAppearance` (Aqua, DarkAqua, Vibrant*, Graphite ...), `CoreTypes` (file type icons), `CoreGlyphsPrivate`, `Dock`, `Finder*`, `ControlCenter`, `Terminal` ...).  `CoreGlyphs` (the SF Symbols, 105 MB) is still missing: GitHub stops at 100 MB per file, so it has to be stored compressed (`xz -9 Assets.car`) or with Git LFS.
