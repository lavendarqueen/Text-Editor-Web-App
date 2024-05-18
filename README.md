# Text-Editor-Web-App

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)
![Babel](https://img.shields.io/badge/Babel/Core-7.15.0-yellow)
![Webpack](https://img.shields.io/badge/webpack-5.51.1-blue)
![Workbox](https://img.shields.io/badge/Workbox-6.2.4-orange)

## Description

Text-Editor-Web-App is a single page web app text editor that meets Progressive Web Application (PWA) requirements - a motivation factor in building the application. The application provides a simple text-editor where the user can record and save notes and/or code snippets. In building this project, I learned about the use of webpack for bundling, Babel for compiling, and Workbox service workers.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contributions](#contributions)
- [Questions](#questions)
- [User Story](#user-story)

## Installation

Installation requires running the following script:

npm run start

## Usage

To use the text editor, click the link to the deployed website:

https://text-editor-web-app.onrender.com

Then click on the "INSTALL" button and starting on or below line 10, start recording and saving your code snippets!

![Text-Editor with code snipped](/client/dist/assets/screenshots/ScreenshotTextEditor.png)

## Credits

I collaborated with Tutor Megan Meyers.

I also consulted the following third-party assets:

Starter code from the University of Denver Coding Bootcamp: https://github.com/coding-boot-camp/cautious-meme

## License

![License](https://img.shields.io/badge/License-MIT-blue.svg)

Copyright (c) 2024 Phyllis Ann Lataille

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contributions

Any contributions made in the spirit of sharing ideas and concepts, will be greatly appreciated. If you have any suggestions that would make this app better, please fork the repo and create a pull request. You can also open an issue with the tag "contribute". Please give this project a star!

### Instructions for forking:

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/fileName)
3. Commit your Changes (git commit -m)
4. Push to the Branch (git push origin feature/newFeature)
5. Open a Pull Request

## Questions

Please reach out by email or visit my GitHub account with any questions:

- Email: lataillep@gmail.com
- GitHub: https://github.com/lavendarqueen/
- Deployed Website: https://text-editor-web-app.onrender.com
- GitHub Repository: https://github.com/lavendarqueen/Text-Editor-Web-App

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

### Acceptance Criteria

GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
