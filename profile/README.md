# Kailash OS

[![License: BSD-3-Clause](https://img.shields.io/badge/licence-BSD--3--Clause-blue)](https://github.com/kailash-os/kailash-os/blob/master/LICENSE) [![release](https://img.shields.io/badge/release-2026.01--alpha.1-blue)](https://github.com/kailash-os/kailash-os/releases) [![Site](https://img.shields.io/website?down_message=offline&up_message=live&url=https%3A%2F%2Fkailash.site)](https://kailash.site) [![Roadmap](https://img.shields.io/badge/roadmap-Kailash%20Roadmap-8A2BE2)](https://github.com/orgs/kailash-os/projects/1) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/kailash-os/kailash-os/badge)](https://scorecard.dev/viewer/?uri=github.com/kailash-os/kailash-os)

Kailash is a NixOS-based Linux distribution for AI security — offensive
(ATTACK), defensive (DEFENCE), classic (CLASSIC), and platform (OPS) tooling in
one declaratively built, reproducibly released environment.

## Project Status:

**`2026.01-alpha.1` — the first staged cut is out** (bare `2026.01` is
reserved for GA; the full policy: [releases.md](https://github.com/kailash-os/kailash-os/blob/master/docs/guide/releases.md)).
The complete release-candidate surface ships on [kailash.site](https://kailash.site);
the roadmap and build backlog live on the [Kailash Roadmap project board](https://github.com/orgs/kailash-os/projects/1)
— issues in [kailash-os/kailash-os](https://github.com/kailash-os/kailash-os).
The documentation estate carries the user and administrator guide at
[docs.kailash.tools](https://docs.kailash.tools) and task-oriented recipes
in the [Kailash OS Cookbook](https://book.kailash.tools).

Contact [shain.singh@owasp.org](mailto:shain.singh@owasp.org) for more information.

## Documentation estate

- [kailash.site](https://kailash.site) — project home: overview, taxonomy, architecture, the paper, the roadmap.
- [docs.kailash.tools](https://docs.kailash.tools) — user and administrator guide with a man-style reference page for every tool in the catalogue.
- [book.kailash.tools](https://book.kailash.tools) — the cookbook: task-oriented recipes (Problem → Solution → Discussion → See also).

## Repositories

- [kailash-os](https://github.com/kailash-os/kailash-os) — the OS: NixOS flake, spec, release engineering.
- [kailash-packages](https://github.com/kailash-os/kailash-packages) — the tool manifest and package overlay.
- [kailash-website](https://github.com/kailash-os/kailash-website) — kailash.site and the paper.
- [kailash-docs](https://github.com/kailash-os/kailash-docs) — the guide at docs.kailash.tools.
- [kailash-book](https://github.com/kailash-os/kailash-book) — the cookbook at book.kailash.tools.
- [kailash-references](https://github.com/kailash-os/kailash-references) — vendored upstream reference repositories.
- [.github](https://github.com/kailash-os/.github) — this org profile.

## FAQ

Q. Why the name 'Kailash'?<br>
A. The authors have been long-time users and fans of WHAX/SLAX, BackTrack/Knoppix and Kali Linux. The name "Kailash" is an acknowledgement to credit Kali Linux as the main source of inspiration.
Kailash is also the residence of Lord Shiva in Hindu scriptures.

Q. Why is Kailash based on NixOS and not {Debian|Arch}? <br>
A. The authors have only recently started learning Nix and NixOS and this project provided an opportunity to do a deep-dive.

## Acknowledgements

- [Kali Linux](https://kali.org)
- [NixOS](https://nixos.org)
- [Spectrum](https://spectrum-os.org)
- [KaliNix](https://github.com/balsoft/kalinix/)
- [Nix Security Box](https://github.com/fabaff/nix-security-box)
- [RedNix](https://github.com/redcode-labs/RedNix)
