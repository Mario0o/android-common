# Claude for OSS & Codex for OSS Readiness

## Project Overview
- **Project**: Trinea Android Common (`android-common`)
- **Mission**: provide ready-to-use cache implementations, UI widgets, and utility helpers so Android teams can bootstrap stable apps quickly.
- **Scope**: image/network/cache layers, pull-to-refresh and paging widgets, DownloadManager extensions, shell/package/file/json utilities, etc.

## Governance & Compliance
- **License**: Apache License 2.0.
- **Maintainer**: [Trinea](https://github.com/Trinea); decisions shared via GitHub Discussions, Issue templates, and CodeKK.
- **Contribution flow**: Fork → feature branch → PR with CLA confirmation → unit tests/static analysis → review → merge.
- **Distribution**: Gradle/Maven Central (`cn.trinea.android.common:trinea-android-common`) plus Dev Tools App scaffolds.

## Impact
- Used by thousands of domestic and international apps, 5k+ GitHub stars.
- Referenced by InfoQ, GeekTime, and enterprise templates to teach caching/tooling patterns.
- Maven Central downloads historically exceed 100k/month, validating real-world demand.

## Claude for OSS Plan
1. **Docs modernization**: Claude helps refresh multilingual README/API guides and migration docs.
2. **Issue triage**: summarize duplicate issues, propose first-pass diagnostics, and improve response quality.
3. **Knowledge transfer**: generate design docs/comments so new maintainers can onboard faster.

## Codex for OSS Plan
1. **AndroidX migration**: Codex assists with scripts that port legacy support APIs to AndroidX and upgrade AGP/Gradle.
2. **Test coverage**: auto-generate unit/instrumentation tests for caches and utilities.
3. **Performance insights**: use Codex to script benchmarks/LeakCanary configurations and analyze regressions.

## Responsible AI Use
- Every AI-assisted change is reviewed and annotated in PRs/releases.
- Sensitive logs or proprietary data are never uploaded; data is anonymized when needed.
- Rollback mechanisms and audit history ensure traceability.

## Support Needs
1. Align modules with AndroidX + Kotlin best practices and publish a refreshed release.
2. Raise test coverage above 50% and add benchmarking.
3. Update samples/docs with modern Compose-centric guidance.

## Contact
- Email: [trinea.cn@gmail.com](mailto:trinea.cn@gmail.com)
- Issues: https://github.com/Trinea/AndroidCommon/issues

> Use this document when submitting Claude for OSS / Codex for OSS applications.
