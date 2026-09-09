# 99quest static trial distribution

- Purpose: Serve the reviewed classroom trial for multiplication worlds 1 and 2.
- Entry: index.html is the complete offline-compatible game. README.md gives controls and storage behavior.
- Safety: Never include learner records, development histories, credentials, analytics, or remote data storage. Preserve local records and the approved identity assets.
- Build/test: No build in this distribution repository. Obtain a verified single-file build from the development project and verify its SHA-256 before publishing. Local preview: python3 -m http.server 8080 --bind 127.0.0.1.
- Done: Validated artifact hash, real browser startup/input/save verification, Pages deployment succeeds, and the live file matches the artifact. Classroom network filtering remains a separate device check.
