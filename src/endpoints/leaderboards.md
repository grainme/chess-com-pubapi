# Leaderboards

## Leaderboards
- **Endpoint**: `https://api.chess.com/pub/leaderboards`
- **Response**: Lists top 50 players in various categories.

Example:
```json
{
  "daily": [
    {
      "player_id": 123,
      "@id": "https://api.chess.com/pub/player/erik",
      "url": "https://api.chess.com/pub/player/erik",
      "username": "erik",
      "score": 100,
      "rank": 1
    }
  ],
  "daily960": [
    {
      "player_id": 456,
      "@id": "https://api.chess.com/pub/player/hikaru",
      "url": "https://api.chess.com/pub/player/hikaru",
      "username": "hikaru",
      "score": 95,
      "rank": 2
    }
  ]
}
```
