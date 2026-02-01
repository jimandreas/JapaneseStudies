# Japanese Vocabulary Study Tool

A single-page web application for learning Japanese vocabulary across two categories: **Restaurant Menu** items and **Japanese Garden** features.

## Features

- **Two study modes** — tabbed interface to switch between 51 restaurant/food terms and 41 garden vocabulary words
- **Audio pronunciation** — click the play button next to any word to hear it spoken in Japanese via the Web Speech API
- **Kanji with readings** — each entry shows the Japanese text (kanji/katakana) alongside its romaji reading and English translation
- **Responsive layout** — two-column grid on desktop, single column on mobile

## Usage

Open `index.html` in a modern browser (Chrome or Edge recommended for best Web Speech API support). No build step, server, or dependencies required.

## Data Sources

- `menuItems.json` — restaurant and food vocabulary (sushi, ramen, drinks, utensils, etc.)
- `gardenFeatures.json` — traditional Japanese garden elements (lanterns, bridges, plants, rock arrangements, etc.)

## Requirements

- A browser that supports the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- A Japanese voice pack installed on the OS for accurate pronunciation (most modern systems include one by default)
