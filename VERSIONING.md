# Legal document versioning

Released legal documents are append-only snapshots under `versions/vN/`. Version 1 is the baseline shipped with Yuli's Drift schema v8 legal-review flow.

## Rules

1. Never edit a released file under `versions/`.
2. A material change creates a new version directory containing all four finalized bilingual documents.
3. Update the latest root documents and their visible version metadata.
4. Coordinate the release with the matching constants and immutable URLs in Yuli's `lib/core/privacy/legal_document_policy.dart`.
5. Verify GitHub Pages URLs before releasing the app.

Material changes include processing purposes, data categories, recipients, retention, user rights, or contractual obligations. Editorial fixes that do not change meaning do not require an app review, but they must not rewrite an immutable snapshot.

Privacy Notice acknowledgement, Terms acceptance, and purpose-specific consent are separate concepts. Optional processing requires its own consent and withdrawal control when consent is the applicable basis.
