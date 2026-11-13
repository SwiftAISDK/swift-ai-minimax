# Changelog

## 1.3.0

- Add MiniMax H3 image generation and reference-image editing with typed options, partial-failure warnings, usage/size metadata and protected unauthenticated image downloads. Existing settings initializer remains available. Reviewed npm delta: @ai-sdk/minimax 3.0.76 to 3.0.81. Validation: `node Scripts/test-packages.mjs` passed all 52 owning suites and 1731 facade tests; tooling 27/27, generation/isolation checks, standalone exports and 106 minimum/latest consumers, documentation check and 101-page build passed. Publication requires green exact-source Swift 6.3.3 CI. Paid/live verification and full-package parity are not claimed.
  Compatibility: Additive native APIs or capabilities under the project minor-release convention. npm baselines and Swift SemVer are independent; this reviewed delta does not establish full-package or live-service parity.
