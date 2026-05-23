# atlas

## what the project is

atlas is a private travel guide web application. it acts as a digital interactive book for organizing travel plans and memories.

## why i made it

i built atlas to track my travel experiences in a private space. logging measurable achievements and seeing clear progression motivates me. this application allows me to log journeys, document climbing routes, and organize sightseeing spots clearly. it keeps my memories organized without relying on generic applications.

## how it was made

i built this application entirely with native web technologies. html creates the book layout. css handles the visual theme and page-turning animations. javascript drives the user interactions. the localstorage api saves user data directly to the browser for persistent offline access. custom javascript using the canvas api renders the interactive color wheel. the filereader api processes local image uploads and handles data backups.

## how the project is organized

the application functions like a book with distinct navigational layers.

- **start menu**: the initial interface for importing data, exporting data, and toggling the display theme.
- **global level**: a master list accessed via the globe icon. it stores high-level country bookmarks.
- **country level**: selecting a country moves its bookmark to the left page. the right page displays a customizable image and an expanding text box for general trip details.
- **category level**: each country contains six specific sub-categories. these are cities, districts, dining, shopping, sightseeing, and climbing. clicking a category opens a detailed list on the left page.
- **item level**: selecting a specific item reveals its dedicated image and description box on the right page. items also feature toggle buttons for ‘favorite’ and ‘wishlist’ statuses. city and district items contain nested sub-lists to further organize locations.
