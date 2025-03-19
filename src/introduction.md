# Introduction

**Disclaimer**: This mdBook is **not an official Chess.com resource**. It is an organized and structured version of the Chess.com Public API documentation, created to help me (and maybe also you) access information more quickly. 

For the most accurate and up-to-date information, always refer to the official Chess.com API announcement page: [Chess.com Published Data API](https://www.chess.com/announcements/view/published-data-api).

---

The Chess.com Public API (PubAPI) is a read-only REST API that provides access to public data available on the Chess.com website. This includes player data, game data, club information, and more. The API responds with JSON-LD data, making it easy to integrate into various applications.

---

### Key Features
- **Public Data Only**: No private or logged-in user data.
- **Read-Only**: Retrieve data but cannot send moves or commands.
- **JSON-LD Responses**: Data is returned in JSON format with linked data contexts.
- **Caching**: Data is cached and refreshed every 12-24 hours.
- **Rate Limits**: Avoid parallel requests to prevent being blocked.
