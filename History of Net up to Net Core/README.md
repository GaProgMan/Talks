# From .NET Framework to .NET Core

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