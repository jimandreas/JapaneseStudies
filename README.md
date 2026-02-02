# Japanese Vocabulary Study Tool

A single-page web application for learning Japanese vocabulary across three categories: **Restaurant Menu** items, **Japanese Garden** features, and **Tourist Phrases**.

## Features

- **Three vocabulary lists** — tabbed interface with 51 restaurant/food terms, 41 garden vocabulary words, and 25 tourist phrases
- **Flashcard mode** — study any dataset with reveal-and-grade flashcards, with score tracking
- **Multiple choice quiz** — test your knowledge with randomized four-option quizzes
- **Audio pronunciation** — click the play button next to any word to hear it spoken in Japanese via the Web Speech API, with adjustable speech speed
- **Character hover tooltips** — hover over any Japanese character to see its type (Kanji/Hiragana/Katakana), romaji for kana, or meaning and reading for kanji
- **Kanji with readings** — each entry shows the Japanese text (kanji/katakana) alongside its romaji reading and English translation
- **Responsive layout** — two-column grid on desktop, single column on mobile

## Usage

Open `index.html` in a modern browser (Chrome or Edge recommended for best Web Speech API support). No build step, server, or dependencies required.

### View Online

[Launch the app in your browser](https://www.jimandreas.com/JapaneseStudies/)

## Data Sources

- `menuItems.json` — restaurant and food vocabulary (sushi, ramen, drinks, utensils, etc.)
- `gardenFeatures.json` — traditional Japanese garden elements (lanterns, bridges, plants, rock arrangements, etc.)

## Requirements

- A browser that supports the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- A Japanese voice pack installed on the OS for accurate pronunciation (most modern systems include one by default)

## Credits

- **Google Gemini** — initial program requirements and vocabulary data
- **Claude Code (Anthropic)** — application implementation
