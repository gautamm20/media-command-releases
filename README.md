# Media Command Browser releases

Builds of Media Command Browser for Apple silicon, published by CI from a private source repository.

- Each version is a release with a zip and `SHA256SUMS`.
- The `feed` release holds the update manifests the app reads. They are signed with Media Command's Ed25519 update key; the app refuses anything else.

The builds are ad-hoc signed (no Apple Developer ID). On first install, right-click the app and choose Open. Later versions install from inside the app.
