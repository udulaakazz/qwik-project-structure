# Routes Folder

The "routes" folder in this project is dedicated to handling the routing logic. It serves as the central place for defining URL paths and importing the correct page components from the "components/pages" folder.

## Purpose

The main purpose of this folder is to keep routing concerns separate from the actual page components, promoting a clean and organized project structure.

## File Structure

The "routes" folder contains directories corresponding to different sections or major pages of the application.

Each section's directory contains an `index.tsx` file. These files are used solely for routing purposes and should import the correct page component from the "components/pages" folder.

## Adding New Routes

When adding a new section or page to the application, follow these steps:

1. Create a new directory inside the "routes" folder with a name that reflects the section or page.

2. Inside the new directory, create an `index.tsx` file.

3. In the `index.tsx` file, import the appropriate page component from the "components/pages" folder.

4. Define the route path and any additional routing configuration using your frontend framework's routing system.

## Framework Compatibility

This project's routing structure is designed to be compatible with our chosen frontend framework (Qwik). Please ensure that any changes or additions align with the framework's conventions.

## Contribution Guidelines

To maintain consistency and project clarity, only use the "routes" folder for routing purposes. The actual page components should be placed in the "components/pages" folder.

If you plan to make changes to the routing logic or project structure, please ensure that they align with the overall project architecture and conventions. Discuss major changes with the team before implementation.
