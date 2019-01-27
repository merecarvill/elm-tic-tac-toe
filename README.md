# Tic Tac Toe [![Build Status](https://travis-ci.org/the-wheels-on-the-ouroboros/tikki-takky-tavvi.svg?branch=master)](https://travis-ci.org/the-wheels-on-the-ouroboros/tikki-takky-tavvi)

A Tic tac toe application with an unbeatable computer opponent. Implemented in the Elm programming language.

## Dependencies

- NVM or another node version manager.

## Setup

- `nvm use`
- `npm install`
- `npx elm package install`

## Build

`npx elm make src/Main.elm --output index.html`

## Run

Open `index.html` in your browser.

## Test

- `npm install -g elm-test`
- `npx elm test TestRunner.elm`
