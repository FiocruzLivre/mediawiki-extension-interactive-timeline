# Historical source preservation

This repository preserves the original MediaWiki InteractiveTimeline extension
by Chris Page, previously published at
https://github.com/TheWatcher/InteractiveTimeline (no longer available).

It preserves the original Git history and tags, including v1.9.0 (commit
ef5e003a8bfcfe31f68fa92a55f43ff1699cdb28, 2019-05-11) and the earlier
deployment-relevant commit d906af45ecf962325ec94090860c18a2d44a2f9b
(2016-07-23). The REL1_32, REL1_28, REL1_27, REL1_26, and
REL122_COMPAT historical branches are retained as source references.

This is an independently hosted preservation copy, **not** the original
author's repository and **not** a claim of active upstream maintenance.
Please preserve Chris Page's attribution and the original GPL-2.0-or-later
license (see COPYING and extension.json).

## Compatibility notes

- Version 1.6 uses an external CHAP Timeline submodule; an ordinary Git
  checkout may not include those required assets unless submodules are fetched.
- Version 1.9.0 switched to externally served vis.js and does not use the
  former CHAP Git submodule.
- The original extension has no current maintainer and has not been certified
  for modern MediaWiki releases. Before deploying, test itimeline rendering,
  script loading, content-security-policy behavior, and MediaWiki upgrades.

Downstream projects should prefer exact Git commit references, not the
moving main or historical master branches.
