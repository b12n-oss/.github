<div align="center">

<img src="https://raw.githubusercontent.com/b12n-oss/b12n-oss.github.io/main/assets/b12n-oss-mark-256.png" width="112" alt="">

# b12n-oss

**Burin's Open Source Software**

[Website](https://b12n-oss.github.io) ·
[Personal profile](https://github.com/burinc) ·
[b12n.net](https://b12n.net)

</div>

---

Where **Burin Choomnuan** publishes open source. Mostly Clojure and
ClojureScript, with a run of Jolt work alongside it. Libraries and tools built
for real use first, then written up properly.

> `b12n` is a numeronym for `burinchoomnuan`: the first letter, the twelve in
> between, then the last. The same trick as `i18n` and `k8s`.

## Projects

| project | what it is |
|---|---|
| [mcp-tkx](https://github.com/b12n-oss/mcp-tkx) | A Clojure and ClojureScript library for building Model Context Protocol clients and servers. Five protocol revisions, dual-era sessions, and it runs on the JVM, Node and Babashka. [Docs](https://b12n-oss.github.io/mcp-tkx/) |
| [raygui-jnk](https://github.com/b12n-oss/raygui-jnk) | 24 raygui examples in jank: native Clojure compiled via C++/LLVM, with raygui built as an ordinary jank package. [Docs](https://b12n-oss.github.io/raygui-jnk/) |
| [raylib-jnk](https://github.com/b12n-oss/raylib-jnk) | 209 raylib examples in jank, calling raylib directly through jank's C++ interop. [Docs](https://b12n-oss.github.io/raylib-jnk/) |
| [raylib-clj](https://github.com/b12n-oss/raylib-clj) | 113 raylib examples in JVM Clojure, calling libraylib directly over coffi and JDK 22+'s Panama Foreign Function & Memory API. [Docs](https://b12n-oss.github.io/raylib-clj/) |
| [docs-engine](https://github.com/b12n-oss/docs-engine) | The shared static-site generator behind the documentation for these projects. |
| [b12n-oss.github.io](https://github.com/b12n-oss/b12n-oss.github.io) | The organization homepage, one hand-written file with no build step. |

## Documentation

Most projects here publish through
[docs-engine](https://github.com/b12n-oss/docs-engine), so they carry no site
generator of their own. You write markdown plus a short config file, and each
site lands at `b12n-oss.github.io/<repo>/`.

Four sites publish that way today: [mcp-tkx](https://b12n-oss.github.io/mcp-tkx/)
(fourteen pages covering getting started, architecture, the 2026-07-28
stateless revision, kebab-case key handling, and a containerised REPL smoke
test), [raygui-jnk](https://b12n-oss.github.io/raygui-jnk/),
[raylib-jnk](https://b12n-oss.github.io/raylib-jnk/), and
[raylib-clj](https://b12n-oss.github.io/raylib-clj/) -- the last three all
moved here from a standalone `.b12n.app` domain.

## Elsewhere

[github.com/burinc](https://github.com/burinc) is the personal account, and the
longer story of what all of this is for. Writing and notes that did not fit in a
repository go to [b12n.net](https://b12n.net).
