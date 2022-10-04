---
title: 'Vue Component Testing'
---

## Framework Support

Cypress Component Testing supports Vue 2+ in a variety of different frameworks:

- Vue CLI
- Nuxt
- Vue with Vite
- Custom Webpack Config

## Tutorial

Visit the [Vue Quickstart Guide](/guides/component-testing/quickstart-vue) for a
step-by-step tutorial.

## Installation

To get up and running with Cypress Component Testing in Vue, install Cypress
into your project:

```bash
npm i cypress -D
```

Open Cypress:

```bash
npx cypress open
```

The Cypress Launchpad will now open and guide you through the configuring your
project.

Whenever you run Cypress for the first time, the app will prompt you to set up
either E2E Testing or Component Testing. Click on "Component Testing" to start
the configuration wizard.

<DocsImage 
  src="/img/guides/component-testing/select-test-type.jpg" 
  caption="Choose Component Testing"> </DocsImage>

The Project Setup screen automatically detects your framework and bundler. Click
"Next Step" to continue.

<DocsImage 
  src="/img/guides/component-testing/project-setup-vue.jpg" 
  caption="Vue and Vite are automatically detected"> </DocsImage>

The next screen checks that all the required dependencies are installed. All the
items should have green checkboxes on them, indicating everything is good, so
click "Continue".

<DocsImage 
  src="/img/guides/component-testing/dependency-detection-vue.jpg" 
  caption="All necessary dependencies are installed"> </DocsImage>

Next, Cypress generates all the necessary configuration files and gives you a
list of all the changes it made to your project.

<DocsImage 
  src="/img/guides/component-testing/scaffolded-files.jpg" 
  caption="The Cypress launchpad will scaffold all of these files for you">
</DocsImage>

After setting up component testing, you will be at the browser selection screen.

Pick the browser of your choice and click the "Start Component Testing" button
to open the Cypress test runner.

<DocsImage 
  src="/img/guides/component-testing/select-browser.jpg" 
  caption="Choose your browser"> </DocsImage>

Your Vue project is now set up with Component Testing! For a guide on writing a
test, checkout the [Quickstart](/guides/component-testing/quickstart-vue)
tutorial.