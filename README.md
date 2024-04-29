# Fyle Frontend Challenge
A GitHub repository listing page using the GitHub REST API.

## Features
1. *Search bar*: There should be a search bar present with a button that should allow the user of the app to search by a GitHub username on clicking the search button.
2. *user-not-found*: In case a user is not found by the same, show an empty zero state. The search bar should still be visible.
3. *Pagination*: - Pagination has to be `server`-side (i.e. Do not load all the repositories and paginate on the client)
    - Show a dropdown to select the page size
    - By default, show `10` repositories per page
    - Users should be able to choose a maximum of `100` repositories per page.
4. *show-loader-page*: When the API calls are in progress, showing a skeleton loader wherever applicable.


## Installation

1. Fork this repository to your github account.
2. Clone the forked repository and proceed with steps mentioned below.

### Install requirements
* Install angular cli [Ref](https://angular.io/cli)
* `npm install` in this repository 

## Development server

Run `ng serve` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Testing server
Run `ng test` for a test server.


## Further help

Visit the [Angular Documentation](https://angular.io/guide/styleguide) to learn more.
Styling is to be strictly done with [Tailwind](https://tailwindcss.com/docs/installation).
