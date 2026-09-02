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
| [docs-engine](https://github.com/b12n-oss/docs-engine) | The shared static-site generator behind the documentation for these projects. |
| [b12n-oss.github.io](https://github.com/b12n-oss/b12n-oss.github.io) | The organization homepage, one hand-written file with no build step. |

## Documentation

Projects here publish through
[docs-engine](https://github.com/b12n-oss/docs-engine), so none of them carries
a site generator of its own. You write markdown plus a short config file, and
each site lands at `b12n-oss.github.io/<repo>/`.

The [mcp-tkx guide](https://b12n-oss.github.io/mcp-tkx/) is the one live today.
Fourteen pages covering getting started, architecture, the 2026-07-28 stateless
revision, kebab-case key handling, and a containerised REPL smoke test.

## Elsewhere

[github.com/burinc](https://github.com/burinc) is the personal account, and the
longer story of what all of this is for. Writing and notes that did not fit in a
repository go to [b12n.net](https://b12n.net).
