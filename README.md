![Photo by Alexander Grey on Unsplash](https://user-images.githubusercontent.com/2342458/212698237-c16fbf92-9986-4b22-8e17-f286584436a9.png)

# Kinsta - Jigsaw Starter

An example of how to set **Jigsaw** up to enable deployment on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management
**Jigsaw** is based on Laravel. This means that it's a regular PHP-based application, so Kinsta automatically installs dependencies defined in your `composer.json` file during the deployment process.

## Required buildpacks
> **Warning**
> Your first deploy will fail in most cases because it won't have all the required **Buildbacks**. Remember to set them up after the first deployment.

In most cases you will want the application to also build the CSS/JS files; therefore, you need to add two Buildpacks:
- PHP
- Node JS

## Web Server Setup
When deploying an application Kinsta automatically creates a web process with `npm start`. It can be later altered in the `Processes` tab in the UI.

## What is Jigsaw?
Jigsaw is a static site framework that uses Blade templates to create your page layouts and Markdown to build your content within the templates so you can produce simple static sites without complex coding knowledge. More information is available on the [Jigsaw](https://jigsaw.tighten.com/) website.
