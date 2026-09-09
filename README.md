# Proctorio brand fonts

Static per-weight **Geist** font files used for server-side document/PDF rendering
where variable fonts and `woff2` are not supported (e.g. wkhtmltopdf-based engines
such as Invoiced's PDF renderer).

| File | Weight |
| --- | --- |
| `Geist-Regular.ttf` | 400 |
| `Geist-Bold.ttf` | 700 |

Both are instanced from the official Geist variable font (same file shipped on
proctorio.com). Geist is licensed under the SIL Open Font License 1.1 — see `OFL.txt`.

Served via jsdelivr, e.g.:
`https://cdn.jsdelivr.net/gh/proctorio/brand-fonts@<commit-sha>/Geist-Regular.ttf`
