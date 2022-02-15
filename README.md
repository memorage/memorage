<p align="center">
  <img alt="Memorage logo" src="./static/logo-light.svg#gh-light-mode-only" />
  <img alt="Memorage logo" src="./static/logo-dark.svg#gh-dark-mode-only" />
</p>

**Memorage** is a peer to peer backup service. Set up with a friend to store
backups on each other's computer. Backups are automatic and encrypted.

**Memorage is still very much a work in progress; it is not yet ready for use.**

<!-- ### Download -->

### Features

- Per file backup - only modified files have to be re-encrypted and resent
- Authentication using ED25519 keys
- XChaCha20Poly1305 encryption for backups

### Limitations

- Peer knows how many files are backed up
- Relies on a synchronisation server (which can be self hosted) <!-- TODO link
  to docs page about self hosting -->
- Peer could falsify backups with a modified client

<!-- ### FAQ -->

<!-- ### How to Use -->
