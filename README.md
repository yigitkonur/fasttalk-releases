# Fast Talk releases

This public repository contains only Fast Talk distribution files. The application source is maintained separately.

- [Downloads](https://github.com/yigitkonur/fasttalk-releases/releases) contain versioned macOS app archives.
- [Update feed](https://yigitkonur.github.io/fasttalk-releases/appcast.xml) is the production Sparkle appcast when a release is published.
- [Staging feed](https://yigitkonur.github.io/fasttalk-releases/staging/appcast.xml) is used for two-version update checks before a production release.

Each appcast enclosure is signed with Sparkle Ed25519. The signing key stays outside this repository and outside the app. A new appcast is published only after its archive, signature, hosted bytes, and staged update have been checked.
