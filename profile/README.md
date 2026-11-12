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
| [champaca](https://github.com/b12n-oss/champaca) | A Java runtime inside Jolt, rebuilt from Anthony Green's [OpenLDK](https://github.com/atgreen/openldk). Bytecode becomes Chez Scheme the first time a method runs, so Jolt calls Java libraries in-process with no JVM. Experimental. [Docs](https://b12n-oss.github.io/champaca/) |
| [mcp-tkx](https://github.com/b12n-oss/mcp-tkx) | A Clojure and ClojureScript library for building Model Context Protocol clients and servers. Five protocol revisions, dual-era sessions, and it runs on the JVM, Node and Babashka. [Docs](https://b12n-oss.github.io/mcp-tkx/) |

<details>
<summary><b>raylib in jank and JVM Clojure</b>, 5 repos: bindings, 326 examples and raygui</summary>

| project | what it is |
|---|---|
| [raylib-jnk](https://github.com/b12n-oss/raylib-jnk) | raylib in jank, calling it directly through jank's C++ interop, and the guide to how the examples are written. [Docs](https://b12n-oss.github.io/raylib-jnk/) |
| [raylib-jank-demo](https://github.com/b12n-oss/raylib-jank-demo) | 213 raylib examples in jank, 212 of them ports of raylib's official examples, each its own runnable project. [Gallery](https://b12n-oss.github.io/raylib-jank-demo/) |
| [raylib-clj](https://github.com/b12n-oss/raylib-clj) | raylib bindings for JVM Clojure over coffi and JDK 22+'s Panama Foreign Function & Memory API. [Docs](https://b12n-oss.github.io/raylib-clj/) |
| [raylib-clj-demo](https://github.com/b12n-oss/raylib-clj-demo) | 113 raylib examples in JVM Clojure, each its own runnable project. [Gallery](https://b12n-oss.github.io/raylib-clj-demo/) |
| [raygui-jnk](https://github.com/b12n-oss/raygui-jnk) | 24 raygui examples in jank: native Clojure compiled via C++/LLVM, with raygui built as an ordinary jank package. [Docs](https://b12n-oss.github.io/raygui-jnk/) |

</details>

<details>
<summary><b>One program, four runtimes</b>, 2 repos: Pac-Man and lisp-games in babashka, JVM Clojure, jank and Jolt</summary>

| project | what it is |
|---|---|
| [raylib-pacman](https://github.com/b12n-oss/raylib-pacman) | One Pac-Man written four times, in babashka, JVM Clojure, jank and Jolt, with nothing shared between them, so each FFI's limits read side by side. [Docs](https://b12n-oss.github.io/raylib-pacman/) |
| [lisp-games](https://github.com/b12n-oss/lisp-games) | Small graphical programs across the same four runtimes, with compute and draw timed separately. [Docs](https://b12n-oss.github.io/lisp-games/) |

</details>

<details>
<summary><b>AWS Lambda, five ways</b>, 5 repos: Jolt, jank, ClojureScript, Rust through Jolt, and Babashka</summary>

| project | what it is |
|---|---|
| [lambda-mvp-jlt](https://github.com/b12n-oss/lambda-mvp-jlt) | An AWS Lambda custom runtime in Jolt (native Clojure on Chez Scheme), with a bench tool for a cold-vs-warm boot-time comparison against your own AWS account. [Docs](https://b12n-oss.github.io/lambda-mvp-jlt/) |
| [lambda-mvp-jnk](https://github.com/b12n-oss/lambda-mvp-jnk) | The same Lambda demo in jank (native Clojure compiled to native code via C++/Clang/LLVM), deployed as a container image. [Docs](https://b12n-oss.github.io/lambda-mvp-jnk/) |
| [lambda-mvp-cljs](https://github.com/b12n-oss/lambda-mvp-cljs) | The same demo in ClojureScript on AWS's managed Node runtime. [Docs](https://b12n-oss.github.io/lambda-mvp-cljs/) |
| [lambda-mvp-rst](https://github.com/b12n-oss/lambda-mvp-rst) | The Jolt runtime again, with its JSON response built by Rust through jolt-diplomat. [Docs](https://b12n-oss.github.io/lambda-mvp-rst/) |
| [lambda-mvp-bb](https://github.com/b12n-oss/lambda-mvp-bb) | The same demo in Babashka via blambda, the only one of the five shipped as a Lambda Layer. [Docs](https://b12n-oss.github.io/lambda-mvp-bb/) |

</details>

<details>
<summary><b>The homepage</b></summary>

| project | what it is |
|---|---|
| [b12n-oss.github.io](https://github.com/b12n-oss/b12n-oss.github.io) | The organization homepage, one hand-written file with no build step. |

</details>

Only public repositories are listed. Some work stays private until it's ready to show,
and it joins this table when it goes public.

## Documentation

Every project above with a docs link publishes through
[jlt-commons/docs-engine](https://github.com/jlt-commons/docs-engine), so none of them
carries a site generator of its own. You write markdown plus a short config file, and
each site lands at `b12n-oss.github.io/<repo>/`. That's fourteen sites today. The
largest are [champaca](https://b12n-oss.github.io/champaca/) and
[mcp-tkx](https://b12n-oss.github.io/mcp-tkx/), at fourteen pages each, and the raylib
galleries show every example with its recording.

## Elsewhere

[github.com/burinc](https://github.com/burinc) is the personal account, and the
longer story of what all of this is for. Writing and notes that did not fit in a
repository go to [b12n.net](https://b12n.net).
