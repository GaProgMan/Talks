# Blazor - You want to run .NET Where?!

This talk was originally written and prepared for Umbraco Festival UK 9 (Friday 9th, 2018).

It covers a little on the history of HTML, CSS and JavaScript before going into detail on what Blazor is and showing two examples of it's usage.

The two examples are:

- [PokeBlazor](https://pokeblazor.azurewebsites.net/)
- UmBlazor
  - This is not online at the momentm, but the source will be being uploaded to GitHub soon.

## Requirements

The following pieces of software are required to build and run this slide deck:

- [node (4.0.0 or later)](http://nodejs.org/)
- yarn
  - because it's better than npm
- grunt


## Running The Presentation

Assuming that you have a terminal open in the root of the repo:

- `npm ci`
  - This will require that there is a `package-lock.json` file.
  - If this is not present, you can force one to be created by running `npm install`
- `npm start`

A web browser should open, point at [localhost:5500](localhost:5500/), and the slide deck will be available to view.

Remember to run it with the slide annotations/notes visible by pressing `s` before running through them.