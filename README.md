# Forked from https://github.com/mrk-its/bevy_webgl2_app_template for learning purposes

Link to demo github page: https://byunei.github.io/bevy_webgl2_app_template

Notes to self:
* Since the path to `wasm.js` in [./index.html](./index.html) has been changed for the github page, you have to run `github_page.sh` before `cargo make serve`.
* Mouse movement does not work in wasm. Bevy has an [open issue](https://github.com/bevyengine/bevy/issues/1166) for this (link to the issue includes a workaround).

# Template of multi-target (WASM / Native) Bevy's application

## Prerequisites

```
cargo install cargo-make
```

## Build and serve WASM version
```
cargo make serve
```
then point your browser to http://127.0.0.1:4000/


## Build and run native version
```
cargo make run
```

![Screenshot](https://mrk.sed.pl/bevy-showcase/assets/bevy_webgl2_app_template.png?v=3)

