# webspace-sdk/run

Versioned builds of the [Webspace Engine](https://github.com/webspace-sdk/webspace-engine), served from
**https://webspaces.space/run/**.

The stable engine is still `<script src="https://webspace.run"></script>`. Builds here are previews of
what's next and are kept forever at their versioned URL, so a world that pins one never breaks.

| Version | URL | What's new |
|---|---|---|
| `0.10.0-alpha.2` | https://webspaces.space/run/0.10.0-alpha.2/webspace.js | Night skies (dark sky colors), `webspace.environment.fog`/`wrap` = off for big scenes, `mix-blend-mode`/`opacity` on splats, any CSS transform (`rotateX()` etc.) |
| `0.10.0-alpha.1` | https://webspaces.space/run/0.10.0-alpha.1/webspace.js | Gaussian splats (`<model src="*.spz\|*.ply\|*.splat">`), Live DOM scripting (`window.webspace`, DOM events for in-world clicks) |

```html
<script src="https://webspaces.space/run/0.10.0-alpha.2/webspace.js"></script>
```

Put [`webspace.service.1.0.1.js`](https://webspaces.space/webspace.service.1.0.1.js) next to your world's HTML when hosting it.

Engine source is MPL-2.0; see [LICENSE](LICENSE). Built from webspace-engine `8319c0fb2`.
