# QuiAppelle Android build

This branch contains the private-use Android MVP source payload and a GitHub Actions workflow that:

- verifies the source archive SHA-256 before extraction;
- builds with JDK 17, Gradle 9.4.1 and Android SDK 36;
- verifies the generated debug APK signature;
- publishes the installable APK as a workflow artifact.

No API key, backend secret, phone number, contact data or other personal data is included in the repository.
