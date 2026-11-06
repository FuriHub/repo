# FuriHub

FuriHub provides a signed Flatpak remote for apps built by and for the FuriLabs* user community.

The landing page lists every app and how to install it: **https://furihub.github.io/repo/**

\*_FuriHub is not associated with FuriLabs.  Please see the full text of the disclaimer below._

## Adding an app
 
- **Not a developer, or not sure?** Open an issue with the [Add an app](https://github.com/FuriHub/repo/issues/new?template=add-app.yml) form.
- **Comfortable with Git?** Open a pull request that adds the app to `pond.yml`, using the format in FrogPak's [configuration reference](https://frogpak.org/docs/configuration.html#apps). If the release files aren't named `APP_ID-aarch64.flatpak`, see [Asset patterns](https://frogpak.org/docs/configuration.html#asset-patterns). In the pull request, include the app's license, a link to a release with the aarch64 bundle, and the device and FuriOS version you tested it on.

## Removing an app
 
Use the [Remove an app](https://github.com/FuriHub/repo/issues/new?template=remove-app.yml) form for apps that are abandoned, broken on FuriOS, or not allowed to be redistributed. Developers can also withdraw their app there. Removal takes the app out of FuriHub, but doesn't uninstall copies people already have.
 
## Reporting a malicious app or security problem
 
Please don't open a public issue. [Report it privately](https://github.com/FuriHub/repo/security/advisories/new) instead; see [SECURITY.md](SECURITY.md) for what happens next.
 
## Problems with an app itself
 
Bugs and feature requests go to the app's developer, in the repository linked on its card at [furihub.github.io/repo](https://furihub.github.io/repo/). FuriHub publishes apps as their developers release them and can't fix them.


## Disclaimer

FuriHub is an entirely unofficial, community-run project. It is not affiliated with, sanctioned by, endorsed by, or supported by FuriLabs. FuriLabs is not responsible for FuriHub or its contents. Please do not report issues with FuriHub or the apps listed within it to the FuriLabs team.  FuriLabs and FuriOS are trademarks of their respective owners.

The apps in FuriHub are made by their own developers, not by FuriHub. FuriHub republishes each app as its developer releases it and does not review, test, or audit the apps' code. FuriHub cannot guarantee that any app is safe, works correctly, works on your device, or will keep receiving updates.  All apps are provided "as is", without warranty of any kind. You install and use them at your own risk. FuriHub and its maintainers are not responsible for any loss of data, damage to your device, or other harm that results from installing or using an app from this repository.

Each app is distributed under its own license, shown on its card; see the app's repository for details.
