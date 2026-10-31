# RoomRoute

An original office interactive website concept built for TripBhai.

## Experience

Move between reception, the studio and a meeting space. This original miniature office uses room navigation and a travelling camera to make the space itself the interface.

- Scroll-linked object assembly and camera composition.
- Three named chapters with keyboard-accessible buttons.
- Responsive layouts, pause control and reduced-motion support.
- Local original SVG artwork remains available if WebGL cannot start.
- No backend, payments, tracking, external fonts or API keys.

## Run

Serve this folder over HTTP, for example `python3 -m http.server 8000`, then open localhost:8000. No build or package installation is needed. GitHub Pages serves the repository root.

## Reference and authorship

Inspired by https://vikasbuilds.com/store#office-demo. This is independently written code and artwork, not the creator's source or an exact reproduction. See CREDITS.md for asset provenance and licences. The design remains a concept; any product/venue is fictional.

## Rendering

Three.js is vendored for reliable static hosting. WebGL and the SVG fallback implement the same chapter progression using separate authored scene components. The renderer uses device pixel ratio capped at 2 for performance; this does not claim that all source images are native 4K.

The no-GPU composition also uses credited high-resolution photography, with independently animated clipped layers for garment/food studies. This fallback is a photographic composition rather than real-time 3D.
