# webspace-sdk/run

Versioned builds of the [Webspace Engine](https://github.com/webspace-sdk/webspace-engine), served from
**https://webspaces.space/run/**.

The stable engine is still `<script src="https://webspace.run"></script>`. Builds here are previews of
what's next and are kept forever at their versioned URL, so a world that pins one never breaks.

| Version | URL | What's new |
|---|---|---|
| `0.10.0-alpha.9` | https://webspaces.space/run/0.10.0-alpha.9/webspace.js | Touch taps click world objects (phones and tablets). |
| `0.10.0-alpha.8` | https://webspaces.space/run/0.10.0-alpha.8/webspace.js | Better night lighting (soft ambient, no harsh sun under dark skies). |
| `0.10.0-alpha.7` | https://webspaces.space/run/0.10.0-alpha.7/webspace.js | In-world link clicks follow HTML semantics (`target`), slower pinch-walking on phones, no Enter VR button on phones. |
| `0.10.0-alpha.6` | https://webspaces.space/run/0.10.0-alpha.6/webspace.js | Panorama skies: `<meta name="webspace.environment.sky" content="sky.jpg">` (any equirectangular image). |
| `0.10.0-alpha.5` | https://webspaces.space/run/0.10.0-alpha.5/webspace.js | Emoji objects change with `textContent`; hand tracking and pinch clicks in VR (Quest hands, Vision Pro gaze-and-pinch). |
| `0.10.0-alpha.4` | https://webspaces.space/run/0.10.0-alpha.4/webspace.js | **Immersive VR** (Quest-class headsets): Enter VR button, `webspace.xr.enterVR()`, thumbstick locomotion, snap turn, controller clicks reach world scripts. |
| `0.10.0-alpha.3` | https://webspaces.space/run/0.10.0-alpha.3/webspace.js | Readable ids (`id="door"` works), scripts can change text (`label.innerHTML`), shared state reaches late joiners, safer saves. From branch `webspace-opus-driving`. |
| `0.10.0-alpha.2` | https://webspaces.space/run/0.10.0-alpha.2/webspace.js | Night skies (dark sky colors), `webspace.environment.fog`/`wrap` = off for big scenes, `mix-blend-mode`/`opacity` on splats, any CSS transform (`rotateX()` etc.) |
| `0.10.0-alpha.1` | https://webspaces.space/run/0.10.0-alpha.1/webspace.js | Gaussian splats (`<model src="*.spz\|*.ply\|*.splat">`), Live DOM scripting (`window.webspace`, DOM events for in-world clicks) |

```html
<script src="https://webspaces.space/run/0.10.0-alpha.9/webspace.js"></script>
```

Put [`webspace.service.1.0.1.js`](https://webspaces.space/webspace.service.1.0.1.js) next to your world's HTML when hosting it.

Engine source is MPL-2.0; see [LICENSE](LICENSE). Built from webspace-engine `8319c0fb2`.
