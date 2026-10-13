# Asterveil: Rise Beyond — web demo build

This repository holds **only the built web version** of the Stage 1 demo, served by GitHub
Pages. The source is private. Do not edit it by hand: it is replaced on every publish.

- Built with `tools/web/build_web.sh` in the private game repository (`docs/WEB_BUILD.md`).
- Godot 4.7.2, Compatibility renderer (WebGL 2), single-threaded: no special server headers needed.
- Saves are kept in the browser (IndexedDB) on the player's own device.
