# Repository Manifest

## Primary documents

- `README.md` — Public GitHub profile and portfolio landing page.
- `CHANGELOG.md` — Change history in Keep a Changelog format.
- `SECURITY.md` — Security reporting process and policy.
- `CONTRIBUTING.md` — Contribution process.
- `CODE_OF_CONDUCT.md` — Community participation expectations.

## Brand assets

- `assets/banner.svg` — studio/VASEY profile header using the current near-black, cyan, grid, signal-trace, Bebas/Reddit/mono house system.
- `assets/brand/vm-mark.svg` — Canonical Vasey Multimedia monogram, preserved from the shared VASEY application footer.
- `assets/brand/vai-mark.svg` — Canonical VASEY/AI monogram, preserved from the shared VASEY application footer.
- `assets/divider.svg` — Decorative cyan footer divider.

## Product previews

The six files in `assets/cards/` are source-informed 1280 × 720 SVG interface previews. They share a restrained VASEY/DEV outer frame while retaining each product's native palette and recognizable controls.

- `assets/cards/vizion.svg`
- `assets/cards/reprompter2.svg`
- `assets/cards/ikonik.svg`
- `assets/cards/page-x.svg`
- `assets/cards/styleyes.svg`
- `assets/cards/resourcery.svg`

Versions intentionally remain outside the artwork so that routine releases do not make the visual portfolio inaccurate.

## Product icons

The 192 × 192 PNG files in `assets/icons/` are copied from each product's canonical source repository rather than redrawn.

| Profile asset | Canonical source |
| --- | --- |
| `assets/icons/vizion.png` | `SeanVasey/VIZION: public/icons/icon-192.png` |
| `assets/icons/reprompter2.png` | `SeanVasey/rePROMPTer2: public/icon-192.png` |
| `assets/icons/ikonik.png` | `SeanVasey/IkoniK: public/icons/icon-192.png` |
| `assets/icons/page-x.png` | `SeanVasey/PAGE-X: icon-192.png` |
| `assets/icons/styleyes.png` | `SeanVasey/StyleyeS: icons/icon-192.png` |
| `assets/icons/resourcery.png` | `SeanVasey/reSOURCERY: icons/icon-192.png` |

## Automation and configuration

- `.github/workflows/ci.yml` — Pinned Markdown quality and README link checks on pull requests and pushes to `main`.
- `.github/workflows/summary.yml` — Issue-summary automation.
- `.markdown-link-check.json` — README link-check policy; excludes non-HTTP `mailto:` links.
- `.markdownlint.json` — Repository Markdown policy, including intentional allowances for profile-layout HTML.

## Notes

This repository is documentation-first and does not host an executable backend service. Product deployments and source code live in their linked application repositories.
