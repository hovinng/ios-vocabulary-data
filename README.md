# iOS Vocabulary Data

Public vocabulary word lists for the iOS vocabulary widget app. Three decks, 100 words each, 300 total.

## Decks

| Deck | Words | Difficulty | Raw URL |
|------|-------|------------|---------|
| Communication | 100 | 1-3 | [communication.json](https://raw.githubusercontent.com/hovinng/ios-vocabulary-data/main/communication.json) |
| Business | 100 | 1-3 | [business.json](https://raw.githubusercontent.com/hovinng/ios-vocabulary-data/main/business.json) |
| Travel | 100 | 1-2 | [travel.json](https://raw.githubusercontent.com/hovinng/ios-vocabulary-data/main/travel.json) |

## Format

Each word is a JSON object:

```json
{
  "english": "serendipity",
  "vietnamese": "sự tình cờ may mắn",
  "example": "Finding that book was pure serendipity.",
  "difficulty": 2
}
```

## Update Flow

1. Edit the JSON file (add/edit/remove words)
2. Commit and push to `main`
3. App users tap "Sync" to pull the latest words

No app rebuild required.