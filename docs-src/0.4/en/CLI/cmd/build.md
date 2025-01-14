# Build

The `dx build` command can help you `pack & build` a dioxus project.

```
dioxus-build 
Build the Rust WASM app and all of its assets

USAGE:
    dx build [OPTIONS]

OPTIONS:
        --example <EXAMPLE>      [default: ""]
        --platform <PLATFORM>    [default: "default_platform"]
        --release                [default: false]
```

You can use this command to build a project:

```
dx build --release
```

## Target platform

Use the `platform` option to choose your target platform:

```
# for desktop project
dx build --platform desktop
```

`platform` currently only supports `desktop` & `web`.

```
# for web project
dx build --platform web
```

## Build Example

You can use the `example` option to select a example to build:

```
# build the `test` example
dx build --example test
```