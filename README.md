# GitHub Dev Card

A printable business card generator powered by the GitHub REST API.

**[Try it →](https://aryan-techie.github.io/github-dev-card)**

## What it does
Enter any GitHub username → generates a two-sided printable business card:
- **Front** — avatar, name, bio, location, website
- **Back** — full GitHub contribution heatmap

## Stack
Zero dependencies. Single `index.html`. Vanilla JS + GitHub REST API.

## APIs used
- `api.github.com/users/{username}`
- `github-contributions-api.jogruber.de/v4/{username}`