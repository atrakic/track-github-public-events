# track-github-public-events

A tool to track and archive GitHub public events using GitHub API and Git scraping techniques.

## Overview

This project automatically tracks GitHub public events by periodically fetching data from the GitHub Events API and storing it for analysis and historical reference.

## Features

- Automatic fetching of GitHub public events
- Event data stored in both JSON and SQLite formats
- Historical event tracking through Git version control

## Data Storage

Events are stored in two formats:
- `events.json`: Raw JSON format
- `events.db`: SQLite database (if enabled)

## License

[MIT License](LICENSE)
