# couch-dev-packages

**Development only. Do not add this to a remote you use.**

A scratch Alpine package repository for testing Couch integration packages on
one development remote, before the package system's next protocol version is
released. Everything here is signed with a **throwaway key** that is deleted
when the test is over, and this repository is deleted with it.

- It is **not** the official Couch package feed (`https://packages.couch-os.dev`)
  and nothing here is ever added to it.
- Packages here need a Couch development build with the protocol 3 preview
  switched on. An ordinary Couch answers "This integration needs a newer Couch".
- No keys, passwords or personal data are in this repository: only package
  programs built from the public integration repositories.

Layout (GitHub Pages, branch `gh-pages`): `p3/armv7/APKINDEX.tar.gz` and the
`.apk` files beside it. There is deliberately no `feed.json`.
