# Puzzle Massive

**I am no longer maintaining version 2 of Puzzle Massive.**

Further development of Puzzle Massive version 3 is at
<https://massive.xyz/puzzle>. There are no plans of keeping the version
3 codebase backwards compatible with version 2.

---

## Version 2 (Unmaintained)

A Massively Multiplayer Online Jigsaw Puzzle as a web application. Jigsaw
puzzles are made from randomly generated classic interlocking pieces and can be
5000+ pieces. Players can collaborate on the same jigsaw puzzle in real time.
Other player's piece movements are moderated automatically in order to prevent
abusive behavior.

[![code style: prettier](https://img.shields.io/badge/code%20style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

## Local Install Instructions (TL;DR)

Minimal setup to get it running on your local machine at
[http://localhost:38682/](http://localhost:38682/).

```bash
cd client-side-public && make && cd -
vagrant up
vagrant provision --provision-with shell-init-dev-local
vagrant provision --provision-with shell-testdata-puzzles-quick
```

---

**More documentation is available within the [docs directory](docs/).**

- [Local development guide](docs/development.md) for getting a local version
  running on your own machine.
- [Deployment guide](docs/deployment.md) for deploying to a live server. This
  covers both in-place deployments and blue-green (stateful swap) deployments.
- [Infrastructure as Code](_infra/README.md) documents how the project uses
  [DigitalOcean](https://m.do.co/c/686c08019031) and [Terraform](https://www.terraform.io/)
  for deploying to Development, Test, Acceptance, and Production environments.

## Change Log and History

This project has been moved to GitHub with a fresher git commit history. The
previous git commit history is available upon request. I've chosen to make
Puzzle Massive an open source project under the GNU Affero General Public
License.

**[Changelog since 2.0.0](CHANGELOG.md)**

## License

Puzzle Massive. An online multiplayer jigsaw puzzle.
Copyright (C) Jake Hickenlooper

Only the source code that is used for Puzzle Massive is licensed under the
[GNU Affero General Public License](https://choosealicense.com/licenses/agpl-3.0/).
Content included in this project is licensed under the
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
License.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

[![DigitalOcean Referral Badge](https://web-platforms.sfo2.digitaloceanspaces.com/WWW/Badge%203.svg)](https://www.digitalocean.com/?refcode=686c08019031&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)
