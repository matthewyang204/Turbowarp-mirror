# Mirror

https://matthewyang204.github.io/Turbowarp-mirror/

These are some scripts for making mirrors of [TurboWarp](https://turbowarp.org/).

## How to make your own mirror

If you have a GitHub account, it's easy to make your own mirror with a URL like: `username.github.io/mirror/`

1. Fork the repository on GitHub. The name of the repository determines the path part of the mirror's URL.
3. Go to the "Settings" tab on your fork > Pages > set Source to GitHub Actions.
4. Go to the "Actions" tab on your fork > Enable actions > Deploy to GitHub Pages > Enable workflow.
5. Wait a few minutes and go back to the Pages settings. There will be a link to the live version of your mirror.

The mirror will update automatically around once a week. You can manually trigger updates if you go to Actions > Deploy to GitHub Pages > Run workflow > Run on `main`.

## License

The mirror scripts are licensed under the MIT License (see LICENSE). The website generated by the mirror scripts is licensed under GPL 3.0.

