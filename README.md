# hugo-mock-landing-page
## **Demo** (not real) Static Landing Page generated with Hugo hosted with GitHub pages
Based on hugo-bootstrap-theme

## Branches
* main: source branch
* gh-pages: source for github pages deployment

## Structure
### Top Level Folders
* assets holds SCSS stylesheets
* content holds MD files with text
* layouts holds HTML files
* static holds image files
* themes contains the submodule hugo-bootstrap-theme, which this project is based on
### Files
Standard: LICENSE, README.md, .gitignore, and .gitmodules
config.toml is the hugo config file
publish_to_gh_pages.sh is a utility script to publish the site to GitHub pages
USER-STORIES.md describes use cases for this made-up app

## Run Locally
1. Clone the repo
2. Run `cd hugo-mock-landing-page`
3. Install hugo (> v99 should be good)
3. Run `hugo server`

## Github Actions Deployment Workflow
The workflow used is named 🏗️ Build and Deploy GitHub Pages and is authored by Jérémie Lumbroso (thank you!). This workflow sets up Hugo in a virtual Linux environment, then creates and publishes a branch to place the compiled web files and serves them through Github Pages, with the option to include a custom deployment domain. 
