# Countries

## Country Profile
- **Endpoint**: `https://api.chess.com/pub/country/{iso}`
- **Response**: Provides details about a country.

Example:
```json
{
  "@id": "https://api.chess.com/pub/country/US",
  "name": "United States",
  "code": "US"
}
```

---

## Country Players
- **Endpoint**: `https://api.chess.com/pub/country/{iso}/players`
- **Response**: Lists usernames of players from the country.

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

## Country Clubs
- **Endpoint**: `https://api.chess.com/pub/country/{iso}/clubs`
- **Response**: Lists clubs associated with the country.

Example:
```json
{
  "clubs": [
    "https://api.chess.com/pub/club/chess-com-developer-community",
    "https://api.chess.com/pub/club/team-usa"
  ]
}
```
