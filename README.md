# Unraid templates

Community Apps templates maintained by Giuseppe Giardina ([Your Future Me](https://yourfuture.me)).

| App | Template | Project |
| :--- | :--- | :--- |
| WatchSense | [`templates/watchsense.xml`](templates/watchsense.xml) | https://github.com/peppeg/watchsense |

WatchSense: self-hosted TV series recommendations from your Netflix, Prime Video, Stremio and Trakt history and an OpenAI-compatible LLM of your choice. Image `ghcr.io/peppeg/watchsense` (linux/amd64, linux/arm64).

## Install

Search for **WatchSense** in the Apps tab of Unraid. Defaults: WebUI on port 3000, data in `/mnt/user/appdata/watchsense/data`, runs as `99:100` (`PUID`/`PGID`). The TMDB key and the LLM provider are set in Settings on first start.

## Support

Issues and questions about the app: https://github.com/peppeg/watchsense/issues

## Maintenance notes

- `ca_profile.xml` stays in the repository root.
- One XML file per Docker app under `templates/`; each `TemplateURL` points at the raw GitHub URL of that file.
- After every meaningful XML change run **Validate** and **Scan** at https://ca.unraid.net/submit.

## License

MIT, see [LICENSE](LICENSE). Templates only: each app keeps its own license.
