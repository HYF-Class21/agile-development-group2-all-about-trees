# All About Trees

This is a small webpage dedicated to providing information about trees. The site
features articles, images, and resources related to various types of trees and
their importance to the environment.

## Table of contents

- [All About Trees](#all-about-trees)
  - [Screenshots](#screenshots)
  - [Features](#features)
  - [Technologies](#technologies-used)
  - [Setup](#setup)
  - [Team Members](#team-members)
  - [Instructions for use](#instructions-for-use)

## Screenshots

![Screenshot](./public/wireframe.jpg)

## Features

The website will be split into 3 parts and will include the following features:

- Heading
  - Title
  - Navbar
- Main section
  - Sidebar
  - Main content (images/text)
- Footer
  - Links to contact the creators of the website

## Technologies Used

- Node
- VS Code
- HTML & CSS
- Git & Github
- Figma

## Setup

- Created a group repo on GitHub from a template repo
  - [Group 2 repository](https://github.com/HYF-Class21/agile-development-group2-all-about-trees)
- Added members of the project to the repo
- Cloned the repo
- Created the group issue to track progress of the project

## Team Members

- Alex
- Allan
- Arseniia
- Faisal

## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member _write_ access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- in the _Branches_ section of your repo's settings make sure:
  - The repository
    [requires a review](https://github.blog/2018-03-23-require-multiple-reviewers/)
    before pull requests can be merged.
  - The `master`/`main` branch must "_Require status checks to pass before
    merging_"
  - The `master`/`main` branch must "_Require require branches to be up to date
    before merging_"

</details>
