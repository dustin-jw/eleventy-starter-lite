# Eleventy Starter Lite

A much slimmer starter template for building a site with Eleventy. For those who prefer to add tools when needed rather than delete boilerplate. [Create a new repository from this template](https://github.com/dustin-jw/eleventy-starter-lite/generate).

This template is meant for the lazy developer, and the default configurations should _just work_ for simple projects. It is up to you to add a testing library, a bundler, or additional tooling if you decide that you need it for your project.

## Making the Project Your Own

You will want to update at least a few things to customize the project.

- `package.json`
  - `name`
  - `author`
  - `license` (if using a different one)
- `README.md`: delete irrelevant sections and add any project-specific details
- icons
  - `favicon.svg` and `favicon.png`
  - `maskable_icon.png`
  - `splash_icon.png`
- `manifest.json`
  - `name`
  - `short_name`
  - `description`
  - `icons` (only if you changed the names of existing icons or added new icons)
  - `theme_color`
  - `background_color`
  - `display` (one of `fullscreen`, `standalone`, `minimal-ui`, or `browser`)
- `robots.txt` (empty by default)
- Copy the contents of the `.env.example` file into a `.env` file to set your environment variables (be sure to set these in whichever environments exist for your project)

## Getting Started

This project requires [Node.js](https://nodejs.org) and `npm` (included with Node.js) to build the site and run it in local development. The LTS (Long Term Support) version is recommended for most cases.

Here are the main commands you'll need to run to get the project up and running.

```sh
# install dependencies
npm install

# run the site in development mode
npm start

# build the site for production
npm run build

# lint your code for possible issues
npm run lint

# update dependencies to their latest versions
npm run update-deps
```
