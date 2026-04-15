# Manage Debian OS foundational services.
Provides common Debian OS configuration and convenience wrappers for base OS
configuration and preparation.

> Always use a **static** version.

> 4.x.x release contains breaking changes **requiring** pre-existing role
> changes. Recommend manually reviewing each role. Collection being rapidly
> updated as real-world migration bugs are found.

See [Documentation][a] for development setup, requirements, and submission
practices. See Individual role documentation for usage.

[Install from Galaxy][g].

[Related Collections][h].

### [Releases][b]

 Release | Debian | Ansible | Notes
---------|--------|---------|-------
 4.x.x   | 13     | 2.20    | Ansible 2.20, semantic versioning.
 3.x.x   | 13     | 2.18    | Use Trixie VM Images.
 2.x.x   | 13     | 2.18    | Migrate to Debian Trixie.
 1.x.x   | 12     | 2.18    | Migration from private repository.

## License
[AGPL-3.0 License][c] | [direct link][f]

## Author Information
PGP: [466EEC2B67516C7117C85CE3A0BC35D16698BAB9][d] | [github gist][e]

[a]: https://r-pufky.github.io/ansible_docs
[b]: https://semver.org/spec/v2.0.0
[c]: https://www.tldrlegal.com/license/gnu-affero-general-public-license-v3-agpl-3-0
[d]: https://keys.openpgp.org/vks/v1/by-fingerprint/466EEC2B67516C7117C85CE3A0BC35D16698BAB9
[e]: https://gist.github.com/r-pufky/a8df36977c55b5bb20829267c4c49d22

[f]: https://github.com/r-pufky/ansible_collection_media/blob/main/LICENSE
[g]: https://galaxy.ansible.com/ui/repo/published/r_pufky/deb
[h]: https://galaxy.ansible.com/ui/namespaces/r_pufky