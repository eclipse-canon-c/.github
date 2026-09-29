<p align="center">
  <img src="https://raw.githubusercontent.com/eclipse-canon-c/.github/main/profile/canon-c-components.svg?v=2" alt="Eclipse Canon-C project components" width="920">
</p>

# Eclipse Canon-C Project

Eclipse Canon-C is a project for building C software on a **verified base layer**. The base layer, [Canon-C](https://github.com/eclipse-canon-c/Canon-C), is a header-only C99 library of primitives for explicit memory and error management — overflow-checked arithmetic, slices, arenas and pools, region lifetimes, `option`/`result` types, and containers — with ACSL contracts throughout, verified with Frama-C/WP. Everything else in this organisation is built on it, classified against it, or written about it.

Canon-C is an [Eclipse Foundation](https://projects.eclipse.org/projects/iot.canon-c) project, mentored from the Eclipse ThreadX ecosystem. Code is MIT-licensed; specifications are CC0.

## The repositories

**[Canon-C](https://github.com/eclipse-canon-c/Canon-C) — the base layer.**
Sources, tests, verification drivers, and the deviation record. This is where the library lives and where the verification runs. Start here if you want to use Canon-C or read how it is verified.

**[external-classifications](https://github.com/eclipse-canon-c/external-classifications) — extensions, classified.**
Libraries built on the base layer are classified against Canon-C's canonical format: what an extension must provide, which layer it belongs to, and how it relates to the verified core. Start here if you are building on Canon-C or want to know what already does.

**[academic-related](https://github.com/eclipse-canon-c/academic-related) — the research.**
Papers, preprints, and their artifacts. The verification campaign behind Canon-C is also a study of what a proof residue costs and how far its bookkeeping can be trusted; the drafts and the data a reviewer needs are here.

**[project-website](https://github.com/eclipse-canon-c/project-website) — [eclipse.dev/canon-c](https://eclipse.dev/canon-c).**
The project site: documentation, releases and how to get involved.

`.github` and `.eclipsefdn` hold organisation configuration and are not user-facing.
