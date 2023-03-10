# Mojave HQ PHP Package Repository

## Usage

There are two scripts, triggered via `composer run-script <name>`:

- `build`: If you want to see what the output would be like. This script installs the dependencies and builds your satis static repository on the `public/` folder.
- `deploy`: This triggers the `deploy.sh` script. It's what you would trigger to make deploy, manually or through Continuous Integration, to the `gh-pages` branch of the remote repository to have your Satis hosted on GitHub Pages.
