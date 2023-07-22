# Routes Folder

## Overview

In Qwik City, the `src/routes/` directory is a special directory dedicated to handling the routing of the application. Similar to other frameworks like Next.js, SvelteKit, SolidStart, or Remix, Qwik City follows a file-system-based routing approach.

### Explanation

- `/routes`: This folder contains Qwik page components that define the routes of the application. However, we do not implement the page content directly in this folder. Instead, each page component imports its respective content from the `components/pages/` folder.

## How to Use

1. To add a new page to the application, create a new file in the `components/pages/` folder that represents the content of the page.

2. In the `routes/` folder, create a new file that imports the corresponding page component from `components/pages/` and exports it as the default component for the route. For example:

```javascript
// routes/index.js

import { component$ } from "@builder.io/qwik";
import type { DocumentHead } from "@builder.io/qwik-city";
import { HomePage } from "~/components/pages/home/home-page";

export default component$(() => {
  return (
    <>
      <HomePage />
    </>
  );
});

export const head: DocumentHead = {
  title: "Welcome to Qwik",
  meta: [
    {
      name: "description",
      content: "Qwik site description",
    },
  ],
};
```

Use the routes/ folder only for route handling. The actual content of each page should reside in the components/pages/ folder.

### Additional Notes

- Make sure to follow the defined folder structure to ensure a consistent and organized codebase.

- Use meaningful names for components and pages to improve code readability.

- Feel free to extend or modify the folder structure if required, but keep in mind the principles of organization and separation of concerns.

Happy coding! If you have any questions or need further assistance, feel free to reach out to the team.
