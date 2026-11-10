# Palmimo DevKit apps

Official apps for Palmimo DevKit. This repository is the official app source
for [apps.palmimo.dev](https://apps.palmimo.dev); Palmimo Portal downloads and
installs apps from here.

| Directory | App name | Description |
| --- | --- | --- |
| [teleop](teleop/) | `teleop` | Browser control with live camera video on the same LAN. |
| [companion-realtime](companion-realtime/) | `companion-realtime` | Voice conversation through the OpenAI Realtime API. |

Each app is an independent uv project with its own `pyproject.toml`, `uv.lock`,
and `palmimo.toml`. Run `uv sync` in the app directory and follow its README.

Licensed under [Apache-2.0](LICENSE). See [NOTICE](NOTICE) and each app's
`THIRD_PARTY_NOTICES.md` for third-party attribution.
