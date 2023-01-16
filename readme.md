![Photo by Alexander Grey on Unsplash](https://user-images.githubusercontent.com/2342458/212698237-c16fbf92-9986-4b22-8e17-f286584436a9.png)

# Kinsta - Jigsaw Starter

An example of how to set **Jigsaw** up to enable deployment on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

Get started for free, the first $20 is on us!

[Application Hosting](https://kinsta.com/application-hosting)

[Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management
**Jigsaw** is based on Laravel. This means that it's a regular PHP-based application, so during the deployment process Kinsta will automatically install dependencies defined in your `composer.json` file.

## Required buildpacks
> **Warning**
> Your first deploy will fail in most cases because it won't have all the required **Buildbacks**. Remember to set them up after the first deployment.

In most cases we want our application to also build our CSS/JS files we need to add two Buildpacks:
- PHP
- Node JS

## Web Server Setup
When deploying an application Kinsta will automatically create a web process with `npm start`. It can be later altered in the `Processes` tab in the UI.

## What is Jigsaw?
**Jigsaw** is a framework for rapidly building static sites using the
same modern tooling that powers your web applications.

### Key Features
- Blade templating, just like your Laravel apps.
- Uses Markdown for content-driven pages.

More info on the [Jigsaw](https://jigsaw.tighten.com/) website.
