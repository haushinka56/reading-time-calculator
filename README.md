# Reading Time Calculator

A lightweight, browser-based tool that estimates how long it takes to read a given amount of text, based on word count and reading speed (words per minute).

## Live demo

[https://haushinka56.github.io/reading-time-calculator/](https://haushinka56.github.io/reading-time-calculator/)


## Features

- Input word count and reading speed (WPM)
- Instant calculation of minutes and hours
- Hour/minute (`Hh Mm`) breakdown
- No dependencies, no build step — a single static HTML file

## Usage

Open `index.html` in any browser, or visit the live demo link above. Enter a word count and adjust the words-per-minute value if needed; results update automatically.

## How it works

```
minutes = word_count / words_per_minute
hours   = minutes / 60
```

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools.

## License

MIT
