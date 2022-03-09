# 🪐11ty_test

A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://get11ty-test.com](https://get11ty-test.com)!

## What is 11ty_test?

### For new users

_11ty_test_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. 11ty_test makes it easy to "get up to zero" and start building your site.

### For experienced developers

_11ty_test_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _11ty_test_ as your Jamstack starter:

* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the 11ty_test name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/nemes1s/11ty_test/blob/master/README.11ty_test.md) to help you take the next steps and launch your project!
* Sass for CSS
* Javascript compilation and minification
* Browsersync to preview your work

## Get started: Use This Template

<details open>
 <summary>Right from this README</summary>
 
###  Create a new project using 11ty_test and add it to your GitHub account

 [Click here to use this template](https://github.com/nemes1s/11ty_test/generate)
 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

### Get started from your command line

 ```sh
  gh repo create example.com --template nemes1s/11ty_test
 ```

</details>

## Get to Know 11ty_test

Ready to go deeper? Here's how 11ty_test is laid out:

```sh
example.com                 # → Root of your 11ty_test-based project
├── src/                    # → Source directory
│   ├── assets/             # → Site assets
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── scripts/
│   │   ├── styles/
│   │   └── views/
│   │       └── layouts/
│   │       └── partials/
│   ├── config/             # → Eleventy configuration
│   │   ├── collections.js  # → Add and configure collections (https://www.11ty.dev/docs/collections/)
│   │   ├── filters.js      # → Add and configure filters (https://www.11ty.dev/docs/filters/)
│   │   ├── passthroughs.js # → Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
│   │   ├── plugins.js      # → Add and configure plugins (https://www.11ty.dev/docs/plugins/)
│   │   ├── shortcodes.js   # → Add and configure shortcodes (https://www.11ty.dev/docs/shortcodes/)
│   │   ├── templateLanguages.js   # → Configure custom template languages (HINT: this is where 11ty_test's Sass and Javascript pipelines are set up!) (https://www.11ty.dev/docs/languages/custom/)
│   │   └── watchtargets.js # → Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
│   ├── data                # → Customize site data (https://www.11ty.dev/docs/data/)
│   │   └── navigation.json # → Site navigation configuration
│   └── pages               # → Add "pages" collection items here
│       ├── index.md        # → Default index page
│       └── pages.json      # → Shared pages attributes
├── .eleventy.js            # → Core Eleventy config file
├── netlify.toml            # → Netlify deployment and plugin configuration (optional)
├── README.template.md      # → 11ty_test readme
└── README.md               # → Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration

Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.

## Install project dependencies

```bash
npm i
```

## Run the project locally

```bash
npm run start
```

## Build for production

```bash
npm run production
```
