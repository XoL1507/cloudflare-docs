Here is the README of the `cloudflare-docs` repository:

---

# Cloudflare Docs

**[View the docs →](https://developers.cloudflare.com/)**

## Why Cloudflare Docs is open source

Our documentation is open source so that we can stay connected with our community and quickly implement feedback. Whether you have opened an issue to provide feedback or contributed your own content, your input is valuable.

If you have any feedback for our documentation or are interested in contributing, please refer to our [contribution guidelines.](https://github.com/cloudflare/cloudflare-docs/blob/production/CONTRIBUTING.md)

## Setup

You must have a recent version of Node.js (22+) installed. You may use [Volta](https://github.com/volta-cli/volta), a Node version manager, to install the latest version of Node and `npm`, which is included with Node.js. 

```sh
$ curl https://get.volta.sh | bash
$ volta install node
```

Install the Node.js dependencies for this project using npm or another package manager:

```sh
$ npm install
```

## Development

To run a local development server while making changes to the site, use the following command:

```sh
$ npm run dev
```

This spawns a server accessible at `http://localhost:1111` in your browser. Any changes made within the project, including `content/**` updates, will automatically reload in the browser.

### Recommendations

Part of the application accesses the GitHub API to populate the [Wrangler changelog](https://github.com/cloudflare/cloudflare-docs/blob/production/layouts/partials/wrangler-changelog.html). To increase the rate limit for API requests, you might want to add a [classic token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).

## Deployment

The documentation is deployed using [Cloudflare Pages](https://pages.cloudflare.com). Every commit pushed to production will deploy automatically to [developers.cloudflare.com](https://developers.cloudflare.com).

## For Cloudflare employees

To get write access to this repo, please reach out to the **Developer Docs** room in chat.

## License and Legal Notices

Content in this repository is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/), except as otherwise noted.

Cloudflare products and services referenced in the documentation may be trademarks of Cloudflare in the United States and/or other countries. The licenses for this documentation do not grant the use of Cloudflare trademarks.

---

For detailed commands and further learning resources, check the full README [here](https://github.com/XoL1507/cloudflare-docs/blob/a4eb938738a7e08e022faba9e00b249ad0f11aed/README.md).
