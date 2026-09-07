# $FAST · Gotta Go Fast

A responsive, single-page community landing source with a bold typographic layout,
a featured Sanic image, motion effects, and small browser interaction easter eggs.

**Status:** static frontend source. Token descriptions and origin stories belong to the
page's existing content; on-chain behavior, commercial claims, and hosted availability
have not been independently verified in this documentation pass.

## Implementation highlights

- HTML, CSS, and vanilla JavaScript in a single entrypoint.
- Responsive layout, animated marquee, and a `prefers-reduced-motion` stylesheet branch.
- Contract-address copy control with text-selection fallback.
- Reveal-on-scroll effects through `IntersectionObserver`.
- Keyboard and pointer interactions: a Konami sequence, typed keyword, and click-triggered effects.
- Visibility-aware document title changes and short-lived toast feedback.

## Source map

| File | Responsibility |
| --- | --- |
| [index.html](index.html) | Content, responsive styling, browser interactions, and references |
| [FGjpuf-XIAMFd_M.jpg](FGjpuf-XIAMFd_M.jpg) | Featured Sanic image used by the hero |
| [LRDASku7_400x400.jpg](LRDASku7_400x400.jpg) | Image used in the source-reference card |
| [.gitignore](.gitignore) | Local secret and session-file safeguards |

Typography is requested from Google Fonts: Archivo Black, Space Grotesk,
JetBrains Mono, and Caveat. Image assets are served from the repository.

## Local preview

Requirements: Python 3 and a browser. From the repository root:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000`. No package installation or build stage is required.
A localhost or HTTPS context is useful for exercising the clipboard control.

## Maintenance and manual checks

1. Keep both image files with the HTML when publishing to an existing static host.
2. Update repeated contract references together; the copy control reads the displayed value.
3. Check narrow layouts, the copy control, and scroll-reveal visibility.
4. Exercise the keyboard sequence and click interactions with reduced-motion preferences enabled.
5. Review the source links and project statements before any public content update.

The existing source carries a Telegram/Sanic origin reference and a `$FAST` footer.
Those references are retained in the page, rather than presented here as independently
verified history or proof of affiliation.

## Verification and boundaries

Documentation validation covers the entrypoint, local file references, and inline JavaScript syntax.
The repository has no automated test suite, build system, or deployment workflow.
This is presentation-layer source; it does not contain smart contracts or payment processing.

## Attribution and reuse

Sanic imagery, Telegram identity elements, and font families remain subject to their
respective owners' rights. No repository license file is present. Keep existing credits
and obtain suitable asset permissions before reusing the visual identity in another project.
