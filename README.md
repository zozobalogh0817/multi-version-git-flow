# multi-version-git-flow

A lightweight Git Flow variant for **maintaining multiple active versions in parallel**.

The repository demonstrates a branching strategy where:

* `stable` is the **single, authoritative production branch**
* Versioned `main/x.y` branches (e.g. `main/1.0`, `main/2.0`) represent **independent release lines**
* Hotfixes are applied explicitly and can be forward-ported when needed

Designed for teams supporting **long-living versions**, enterprise systems, and release-driven development—while keeping Git history clean and predictable.