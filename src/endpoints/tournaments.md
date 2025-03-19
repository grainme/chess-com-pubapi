# Tournaments

## Tournament
- **Endpoint**: `https://api.chess.com/pub/tournament/{url-ID}`
- **Response**: Provides details about a tournament.

Example:
```json
{
  "name": "33rd Chess.com Quick Knockouts",
  "url": "https://api.chess.com/pub/tournament/-33rd-chesscom-quick-knockouts-1401-1600",
  "description": "A quick knockout tournament.",
  "creator": "erik",
  "status": "finished",
  "finish_time": 1251846528,
  "settings": {
    "type": "round_robin",
    "rules": "chess",
    "time_class": "daily",
    "time_control": "1/259200",
    "is_rated": true,
    "is_official": false,
    "is_invite_only": false,
    "initial_group_size": 5,
    "user_advance_count": 1,
    "use_tiebreak": true,
    "allow_vacation": false,
    "winner_places": 1,
    "registered_user_count": 5,
    "games_per_opponent": 2,
    "total_rounds": 1,
    "concurrent_games_per_opponent": 1
  },
  "players": [
    {
      "username": "erik",
      "status": "eliminated"
    }
  ],
  "rounds": [
    "https://api.chess.com/pub/tournament/-33rd-chesscom-quick-knockouts-1401-1600/1"
  ]
}
```
