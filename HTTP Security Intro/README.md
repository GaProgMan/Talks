# HTTP Security Intro

This talk was designed to point out common ways that website admins can increase the security of their sites. It covers:

- Plugins

Assuming that the site is powered by a CMS which supports plugins

- A little on why HTTPS is required

With a contrived example of how anyone can intercept HTTP traffic

- A little on SRI

How you can use the `integrity` attribute on a script tag to ensure that the loaded script has not be tampered with

- Content Security Policy

Includes a brief description on what CSP is and lists some other, useful HTTP headers

## Requirements

The following pieces of software are required to build and run this slide deck:

- [node (4.0.0 or later)](http://nodejs.org/)
- yarn
  - because it's better than npm
- grunt


## Running The Presentation

Assuming that you have a terminal open in the root of the repo:

1. `npm ci`
1. `npm start`

A web browser should open, point at [localhost:5500](localhost:5500/), and the slide deck will be available to view.