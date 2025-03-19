# Daily Puzzle

## Daily Puzzle
- **Endpoint**: `https://api.chess.com/pub/puzzle`
- **Response**: Provides information about the daily puzzle.

Example:
```json
{
  "title": "Daily Puzzle",
  "url": "https://www.chess.com/puzzle",
  "publish_time": 1513584000,
  "fen": "rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1",
  "pgn": "1. e4 e5 2. Nf3 Nc6 3. Bb5 a6",
  "image": "https://images.chesscomfiles.com/uploads/v1/puzzle/12345678.12345678.12345678.12345678.200x200o.1234567890abcdef.jpeg"
}
```

---

## Random Daily Puzzle
- **Endpoint**: `https://api.chess.com/pub/puzzle/random`
- **Response**: Provides information about a random daily puzzle.

Example:
```json
{
  "title": "Random Puzzle",
  "url": "https://www.chess.com/puzzle/random",
  "publish_time": 1513584000,
  "fen": "rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1",
  "pgn": "1. e4 e5 2. Nf3 Nc6 3. Bb5 a6",
  "image": "https://images.chesscomfiles.com/uploads/v1/puzzle/12345678.12345678.12345678.12345678.200x200o.1234567890abcdef.jpeg"
}
```
