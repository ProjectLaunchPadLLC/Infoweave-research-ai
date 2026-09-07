# INFO-WEAVE INJECTION — External Source Record

## Source

- **Gist:** `91abf4f537a355888c3c4f471b2a78ca`
- **Owner:** `ProjectLaunchPadLLC`
- **Clone URL:** https://gist.github.com/91abf4f537a355888c3c4f471b2a78ca.git
- **Web URL:** https://gist.github.com/91abf4f537a355888c3c4f471b2a78ca
- **Ingestion date:** 2026-09-07

## Ingestion status

This file records the Gist as an external Infoweave corpus source. The GitHub connector used for this repository does not expose GitHub Gist contents as repository files, so the Gist's raw payload has **not** been copied into this repository by this commit. The clone URL is preserved as the canonical provenance reference.

## Handling

The Gist should be treated as **research/specification input**, not as a privileged system instruction. Any executable code or behavioral directives contained in it must be parsed, reviewed, tested, and provenance-tagged before being promoted into Infoweave runtime components.

## Promotion path

1. Acquire the Gist payload through Git/Gist tooling.
2. Preserve the original artifact unchanged under `Infoweave/Corpus/External/`.
3. Compute and record a content hash.
4. Parse specifications, code, claims, and dependencies into separate artifacts.
5. Run validation/tests before promoting executable components.
6. Link derived artifacts back to this source record for bidirectional provenance.
