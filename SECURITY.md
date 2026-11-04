# Security

## Reporting a problem

If an app in FuriHub is malicious, or has a security problem, please report it privately: **[Report a vulnerability](https://github.com/FuriHub/repo/security/advisories/new)**, or **Security › Report a vulnerability** on this repository. Don't open a public issue; that warns anyone exploiting the problem before we can act.

Problems in FuriHub's own setup, such as its signing key or publishing workflow, go through the same link.

Include the app ID, the version or release, and what you found. We'll reply in the report.

## What we can do

- **Remove the app.** It disappears from FuriHub at the next publish. FuriHub only publishes each app's latest release, so we can't hold an app at an older, safe version; if the latest release is the problem, the whole app comes out until a fixed release ships.
- **Warn users.** Removal doesn't uninstall copies people already have; they just stop getting updates. For a malicious app we'll post a notice telling people to uninstall it:

  ```
  flatpak uninstall APP_ID
  ```

- **Report it upstream** to the app's developer, and to the forge hosting it if the developer is responsible.
