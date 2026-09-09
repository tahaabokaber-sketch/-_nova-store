# GitHub Pages verification

The public repository now contains `index.html`, `404.html`, and `assets/` at the root on `main`.

GitHub Pages API reported `build_type: legacy`, source `main:/`, and status `building` after the latest checkpoint. Two browser checks of `https://tahaabokaber-sketch.github.io/-_nova-store/` still showed the cached GitHub Pages 404 page while the deployment was building. Recheck after the build status changes to `built`; append a cache-busted query if necessary.
