
## Follow-up

The latest GitHub Pages HTML loads the updated asset `index-CaXeETT-.js`, and the browser reports `hostname=tahaabokaber-sketch.github.io` and `pathname=/-_nova-store/`. The page still renders the app's internal `NotFound` route, while the `Back to home` link is correctly prefixed with `/-_nova-store/`. This indicates the current wouter base configuration is not matching the initial subpath reliably; prefer a hash-based router on GitHub Pages for deterministic deployment.
