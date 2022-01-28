# Hashpass
*Minimalist "passphrase" feature for static sites*

When proper authorization/authentication controls are not available, use this simple technique to secure your content.

# Usage

1. Place this file at the root of your web server.
2. Choose a passphrase. For example sake, let's use `secret`.
3. Obtain the SHA1 hash of the passphrase. You can use [this tool](https://passwordsgenerator.net/sha1-hash-generator/).

or if you have `sha1sum`,

```
printf "secret" | sha1sum
e5e9fa1ba31ecd1ae84f75caaa474f3a663f05f4  -
```

4. Create a directory. Use the SHA1 hash from earlier as the name.
5. Store web files in this directory.

# Demo
Try **Hashpass** [here](https://andtechstudios.github.io/hashpass). The passphrase is `secret`.

# References
* [iOS Continuous Integration with GitLab CI, Fastlane & OTA Installation](https://medium.com/@leszek.s/ios-continuous-integration-with-gitlab-ci-fastlane-and-ota-installation-from-gitlab-pages-f312e07ab06e)
* [chrissy-dev/protected-github-pages](https://github.com/chrissy-dev/protected-github-pages)

---

> Credit to [@crissy-dev](https://github.com/chrissy-dev/protected-github-pages) for using `robots` tags
