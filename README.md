# FuriHub

FuriHub provides a signed Flatpak remote for apps built by and for the FuriLab* community.

The landing page lists every app with its install command: **https://furihub.github.io/repo/**

## Adding an app
 
- **Not a developer, or not sure?** Open an issue with the [Add an app](https://github.com/FuriHub/repo/issues/new?template=add-app.yml) form.
- **Comfortable with Git?** Open a pull request that adds the app to `frogpak.yml`, using the format in FrogPak's [configuration reference](https://frogpak.org/docs/configuration.html#apps). If the release files aren't named `APP_ID-aarch64.flatpak`, see [Asset patterns](https://frogpak.org/docs/configuration.html#asset-patterns). In the pull request, include the app's license, a link to a release with the aarch64 bundle, and the device and FuriOS version you tested it on.

## Removing an app
 
Use the [Remove an app](https://github.com/FuriHub/repo/issues/new?template=remove-app.yml) form for apps that are abandoned, broken on FuriOS, or not allowed to be redistributed. Developers can also withdraw their app there. Removal takes the app out of FuriHub, but doesn't uninstall copies people already have.
 
## Reporting a malicious app or security problem
 
Please don't open a public issue. [Report it privately](https://github.com/FuriHub/repo/security/advisories/new) instead; see [SECURITY.md](SECURITY.md) for what happens next.
 
## Problems with an app itself
 
Bugs and feature requests go to the app's developer, in the repository linked on its card at [furihub.github.io/repo](https://furihub.github.io/repo/). FuriHub publishes apps as their developers release them and can't fix them.



*FuriHub is entirely a community-led project and is not sanctioned by or associated with FuriLabs.
