![Zig](https://img.shields.io/badge/zig-heavy-111827?style=for-the-badge&logo=zig&logoColor=f7a41d)

# SmallThingz

Small, focused, high-performance libraries — mostly in **Zig**.

---

## 📡 Web / Network

| Project | Description |
|---|---|
| [**zhttp**](https://github.com/SmallThingz/zhttp) | Low-latency HTTP/1.1 server with comptime routing, typed captures, composable middleware. Benchmarks beat faf. |
| [**zws**](https://github.com/SmallThingz/zws) | RFC 6455 WebSocket primitives — lean frame hot path, `permessage-deflate`, strict validation. |
| [**zhtml**](https://github.com/SmallThingz/zhtml) | GiB/s+ HTML parser + CSS selector engine. Destructive by default, non-destructive opt-in. |
| [**zxml** (fastxml)](https://github.com/SmallThingz/zxml) | Low-latency XML DOM parser — 3.7 GB/s turbo profile, strict mode available. |
| [**alldriver**](https://github.com/SmallThingz/alldriver) | Cross-platform browser automation via CDP + BiDi. Chrome, Firefox, Lightpanda, Electron, WebView2. |

## 📦 Serialization & Memory

| Project | Description |
|---|---|
| [**oneserial**](https://github.com/SmallThingz/oneserial) | Typed single-buffer serialization — validate once, traverse via typed views, decode on demand. |
| [**onealloc**](https://github.com/SmallThingz/onealloc) | Convert nested structs into one contiguous allocation. IPC-ready, cache-friendly. |

## 🏗 Infrastructure

| Project | Description |
|---|---|
| [**ziglibc**](https://github.com/SmallThingz/ziglibc) | Experimental libc in Zig — C stdlib + POSIX surface. Linux/macOS/Windows conformance green. |
| [**libbrotli.zig**](https://github.com/SmallThingz/libbrotli.zig) | Vendored libbrotli with typed Zig helpers + full C API. |
| [**libzstd.zig**](https://github.com/SmallThingz/libzstd.zig) | Vendored libzstd with typed Zig helpers + full C API. |
| [**unarr**](https://github.com/SmallThingz/unarr) | Multi-format archive bindings — RAR, TAR, ZIP, 7z. Zig-managed C build. |

## 🛠 Tooling

| Project | Description |
|---|---|
| [**subdl**](https://github.com/SmallThingz/subdl) | Subtitle scraper with 12 providers, CLI, and Vaxis TUI. |
| [**zig_dotenv**](https://github.com/SmallThingz/zig_dotenv) | Comptime and runtime `.env` loader. Microlibrary — copy it in or fetch it. |

---

## Other

| Project | Description |
|---|---|
| [**timetravel**](https://github.com/SmallThingz/timetravel) | Rolling audio buffer recorder for Android (Kotlin). Disk-backed restore, fast export. |
| [**java_debug_shell**](https://github.com/SmallThingz/java_debug_shell) | Keyword-free scripting language for Java debugging. Full JVM interop, single file. |

---

> *Small thingz, well made.*
