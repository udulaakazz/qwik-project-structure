# Components

This directory contains various components that make up the user interface of the web application. Components are organized into subdirectories based on their functionality and usage.

## Components Structure

- `/common`: Contains components that are shared across multiple pages.
  - `/header`: Contains header component
    - `Header.tsx`: A reusable component for the site's header.
  - `/footer`: Contains footer component
    - `Footer.tsx`: A reusable component for the site's footer.
  - ...
- `/ui`: Contains fundamental UI components used across the application.
  - `/button`: Contains button component
    - `Button.tsx`: A generic button component used across different pages.
  - `/input`: Contains input component
    - `Input.tsx`: A reusable component for input fields.
  - ...
- `/sections`: Holds larger sections or blocks of content used across pages.
  - `/hero`: Contains hero component
    - `HeroSection.tsx`: A section that showcases the hero content.
  - ...
- `/pages`: Each page has its own folder containing page-specific components.
  - `/home`: The home page folder.
    - `HomePage.tsx`: The main component for the home page.
    - `HomeHero.tsx`: A custom hero component specific to the home page.
    - ...
  - `/about`: The about page folder.
    - `AboutPage.tsx`: The main component for the about page.
    - ...
  - ...
- `/widgets`: Contains reusable widgets or self-contained components.
  - `SocialMediaIcons.tsx`: A widget for displaying social media icons.
  - `SubscribeForm.tsx`: A widget for newsletter subscription.
  - ...

Each component folder may contain its own README.md file for further information on usage and implementation.

## Development Guidelines

- For components that are shared across multiple pages, place them in the `/common` folder.
- For fundamental UI components used across different parts of the application, use the `/ui` folder.
- For larger sections or blocks of content used across pages, create them in the `/sections` folder.
- For reusable widgets or self-contained components, use the `/widgets` folder.
- Each page has its own folder under `/pages` containing page-specific components.

Please adhere to these guidelines to keep this project organized and maintainable.

Happy coding!
