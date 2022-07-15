# tailwind-tooltip-phpstorm
minimal reproducible example for tailwind tooling not working properly in my PhpStorm ([YouTrack WEB-56568](https://youtrack.jetbrains.com/issue/WEB-56568/CSS-Tooltip-only-shows-specificity-but-no-Tailwind-styles))

see [src/index.html](./src/index.html)

- minimal project similar to [tailwind installation guide](https://tailwindcss.com/docs/installation)
- added class names from guide and actual project
- included `dist` folder in repository for shared debugging
- loading `css` from `src` AND `dist` folder only for debugging purpose
