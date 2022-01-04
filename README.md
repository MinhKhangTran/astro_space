# Space travel Site

Based on the tutorial of Kevin Powell on [Scrimba](https://scrimba.com/learn/spacetravel)

## Agenda

_Data before Styling_

### Making the pages

- Index
- Destinations
  - Subpages
- Crew
  - Subpages
- Technolgy
  - Subpages

### Fetching data for pages

According to [doc](https://docs.astro.build/en/guides/data-fetching/)

    ---
    // Movies.astro
    const response = await fetch('https://example.com/movies.json');
    const data = await response.json();
    // Remember: Astro component scripts log to the CLI
    console.log(data);
    ---
    <!-- Output the result to the page -->
    <div>{JSON.stringify(data)}</div>`

### Set up the components with semantic HTML

- Navbar
- Button
- Title
- Tabs/dots/Numbers

## Tabs functionality

## Styling

- Variables

  - Colors
  - Font family
  - Font size

- Reset
- Utility classes
- Component and Page specific styles
