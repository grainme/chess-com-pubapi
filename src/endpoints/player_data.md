# Player Data

## Player Profile
- **Endpoint**: `https://api.chess.com/pub/player/{username}`
- **Response**: Returns details like username, title, country, join date, and more.

Example:
```json
{
  "@id": "https://api.chess.com/pub/player/erik",
  "url": "https://api.chess.com/pub/player/erik",
  "username": "erik",
  "player_id": 41,
  "title": "GM",
  "status": "premium",
  "name": "Erik",
  "avatar": "https://images.chesscomfiles.com/uploads/v1/user/12345678.12345678.12345678.12345678.200x200o.1234567890abcdef.jpeg",
  "location": "New York, USA",
  "country": "https://api.chess.com/pub/country/US",
  "joined": 1178556600,
  "last_online": 1500661803,
  "followers": 17,
  "is_streamer": true,
  "twitch_url": "https://twitch.tv/erik",
  "fide": 2800
}
```

---

## Titled Players
- **Endpoint**: `https://api.chess.com/pub/titled/{title-abbrev}`
- **Response**: Lists usernames of players with the specified title.

Example:
```json
{
  "players": [
    "erik",
    "hikaru"
  ]
}
```

---

## Player Stats
- **Endpoint**: `https://api.chess.com/pub/player/{username}/stats`
- **Response**: Provides ratings, win/loss records, and stats for different game types.

Example:
```json
{
  "chess_daily": {
    "last": {
      "date": 1509709165,
      "rating": 1642,
      "rd": 58
    },
    "best": {
      "date": 1256228875,
      "rating": 2065,
      "game": "https://api.chess.com/pub/player/erik/games/2009/10"
    },
    "record": {
      "win": 177,
      "loss": 124,
      "draw": 21,
      "time_per_move": 18799,
      "timeout_percent": 9.99
    }
  }
}
```

---

## Player Online Status
- **Endpoint**: `https://api.chess.com/pub/player/{username}/is-online`
- **Response**: Indicates if the player is currently online.

Example:
```json
{
  "online": true
}
```

---

## Player Games
- **Current Daily Games**: `https://api.chess.com/pub/player/{username}/games`
- **Monthly Archives**: `https://api.chess.com/pub/player/{username}/games/archives`
- **Download PGN**: `https://api.chess.com/pub/player/{username}/games/{YYYY}/{MM}/pgn`
