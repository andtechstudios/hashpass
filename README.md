# Hashpass
*Minimalist "password" feature for static sites*

When proper authorization/authentication controls are not available, use this simple technique to secure your content.

# Usage

1. Place this file at the root of your web server.
2. Choose a pass phrase.

For example
```
secret
```

3. Obtain the SHA1 hash of this pass phrase. (You can use [this tool](https://passwordsgenerator.net/sha1-hash-generator/))

```
fc683cd9ed1990ca2ea10b84e5e6fba048c24929
```

4. Create a directory. Use the SHA1 hash from earlier as the name.
5. Store web files in this directory.

# References
* [iOS Continuous Integration with GitLab CI, Fastlane & OTA Installation](https://medium.com/@leszek.s/ios-continuous-integration-with-gitlab-ci-fastlane-and-ota-installation-from-gitlab-pages-f312e07ab06e)
