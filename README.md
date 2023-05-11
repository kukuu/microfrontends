# Microfrontends: Single SPA v Module Federation:

Micro frontends is a front-end web development pattern in which a single application may be built from disparate builds. It is analogous to a microservices approach but for client-side single-page applications written in JavaScript. It is a solution to de-composition and routing for multiple front-end applications.

With a microfrontend, no single team owns the UI in its entirety. Instead, every team owns a piece of the screen, page, or content. For example, one team might be responsible for the search box, while another might code suggestions based on users' tastes.

The main difference between module federation and single-spa is the way they handle the sharing and reuse of modules.
Module federation uses a central “entry” point for each module, while single-spa uses a “shell” application to load and manage different micro frontends.
