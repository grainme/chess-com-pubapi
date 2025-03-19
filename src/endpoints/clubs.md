# Clubs

## Club Profile
- **Endpoint**: `https://api.chess.com/pub/club/{club-url-id}`
- **Response**: Provides details like club name, description, member count, and creation date.

Example:
```json
{
  "@id": "https://api.chess.com/pub/club/chess-com-developer-community",
  "name": "Chess.com Developer Community",
  "club_id": 57796,
  "icon": "https://images.chesscomfiles.com/uploads/v1/group/12345678.12345678.12345678.12345678.200x200o.1234567890abcdef.jpeg",
  "country": "https://api.chess.com/pub/country/US",
  "average_daily_rating": 1376,
  "members_count": 54,
  "created": 1178556600,
  "last_activity": 1500661803,
  "visibility": "public",
  "join_request": "https://api.chess.com/pub/club/chess-com-developer-community/join",
  "admin": [
    "https://api.chess.com/pub/player/erik",
    "https://api.chess.com/pub/player/hikaru"
  ],
  "description": "A club for Chess.com developers."
}
```

---

## Club Members
- **Endpoint**: `https://api.chess.com/pub/club/{club-url-id}/members`
- **Response**: Lists members grouped by activity level (weekly, monthly, all-time).

Example:
```json
{
  "weekly": [
    {
      "username": "erik",
      "joined": 1178556600
    }
  ],
  "monthly": [
    {
      "username": "hikaru",
      "joined": 1178556600
    }
  ],
  "all_time": [
    {
      "username": "magnus",
      "joined": 1178556600
    }
  ]
}
```
