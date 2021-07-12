# Remote Social
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
### Developed by [**Conrad Trost**](https://github.com/retro1967), [**Joseph DeWoody**](https://github.com/jpd61), and [**Courtney Stanton**](https://github.com/clstanton)

## [Deployed App](https://inspiring-goldstine-2bd17d.netlify.app/)

## Description
#### Search for movies using the TMdB API and save them to your watchlist.

<p align="center">
<img src="./client/src/assets/images/remote-screenshot.png" width="900" title="Screenshot of Remote Social">
</p>

### Table of Contents:

**[Description](#description)**<br>
**[Installation Instructions](#installation-instructions)**<br>
**[Usage Instructions](#usage-instructions)**<br>
**[Contributions](#contributions)**<br>
**[Test Instructions](#test-instructions)**<br>
**[License](#license)**<br>
**[Questions](#questions)**<br>

## Installation Instructions
Clone the repository and run `npm install` in the root directory command line.

This will install all necessary packages in `root`, `client`, and `server` directory.

Open client/package.json and change the proxy to "http://localhost:3001/"

Open client/src/utils/API.js and edit all /graphql paths to be relative paths.
For example, `'https://remote-social-backend.herokuapp.com/graphql/users/me'` => `'/graphql/users/me'`.

Open client/src/App.js, on line 20 change uri to `/graphql`.

## Usage Instructions


In the `root` directory, run `npm run start:dev`. This will run a script to start both `client` and `server`.

## Contributions
Submit a pull request with updated code. All contributions are credited

## Test Instructions
N/A

## License
This application is covered under the [MIT](https://opensource.org/licenses/MIT) license.
Visit the link above to learn more about this license.

## Questions

Find me on [Github](https://github.com/conradtrost)

Check out out my [LinkedIn](https://linkedin.com/in/conradtrost)

Email me with questions at <a href="mailto:conrad@trost.dev">conrad@trost.dev</a>
