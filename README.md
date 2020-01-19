<img align="right" src="docs/img/gemstone-wide-600.png" alt="gemstone logo">

# shared-content
### Gemstone Shared Library Content

When updated, all content in this repo (except this README) is automatically synchronized into all Gemstone Library projects (excluding [root-dev](https://github.com/gemstone/root-dev)) via nightly build scripts.

Be careful to only add content that is applicable to all Gemstone Library projects.

Files can be templated with the following replacement tokens:

| Token              | Replacement                                                      |
|:------------------:|:---------------------------------------------------------------- |
| `{sc:repo-name}`   | Target repository name, kebab-case, e.g, `gemtem`                |
| `{sc:ProjectName}` | Target project name, PascalCase, e.g., `GemTem`                  |
| `{sc:yyyy}`        | Four digit current year, e.g., `2000` from `2000-01-18 15:22:05` |
| `{sc:MM}`          | Two digit current month, e.g., `01` from `2000-01-18 15:22:05`   |
| `{sc:dd}`          | Two digit current day, e.g., `18` from `2000-01-18 15:22:05`     |
| `{sc:HH}`          | Two digit current hour, e.g., `15` from `2000-01-18 15:22:05`    |
| `{sc:mm}`          | Two digit current minute, e.g., `22` from `2000-01-18 15:22:05`  |
| `{sc:ss}`          | Two digit current second, e.g., `05` from `2000-01-18 15:22:05`  |
