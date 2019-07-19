# Talks

Slide decks for talks and presentations that I have given.

Unless indicated (see the nested readmes), each of these talks uses [revealjs](https://revealjs.com/#/). This is an npm technology which allows us to run a Powerpoint-like (or Keynote-like, if you'd prefer) presentation via a web browser.

To start any of the included talks, run the following commands (assuming that you are in the directory of the presentation you want to run):

- `npm ci`

This will install of the packages necessary for you to run the presentation

- `npm start`

This will start a web server, begin serving the presentation, and open your default browser at the location that the presentation is being served from.

## Support This Project

If you have found this project helpful, either as a library that you use or as a learning tool, please consider buying me a coffee:

<a href="https://www.buymeacoffee.com/dotnetcoreshow" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important" ></a>

## Details on the included talks

### NET-IDE

This is a talk covering the tree main IDEs available for .NET development, namely:

- Visual studio
- Visual Studio Code
- JetBrains Jider

### HTTP Security Intro

This talk was designed to point out common ways that website admins can increase the security of their sites. It covers:

- Plugins

Assuming that the site is powered by a CMS which supports plugins

- A little on why HTTPS is required

With a contrived example of how anyone can intercept HTTP traffic

- A little on SRI

How you can use the `integrity` attribute on a script tag to ensure that the loaded script has not be tampered with

- Content Security Policy

Includes a brief description on what CSP is and lists some other, useful HTTP headers
