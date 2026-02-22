# Authentication

All API requests require an API key.

---

## Authentication Method

Authentication is performed using query parameters.

Example:
`https://api.openweathermap.org/data/2.5/weather?q=Goa&appid=YOUR_API_KEY`

---

## Best Practices

- Never expose API keys publicly
- Store keys in environment variables
- Rotate keys periodically

---

## Common Errors

| Code | Meaning |
|---|---|
| 401 | Invalid API key |

---

## Next Step

➡️ Continue to [First API Call](../v1/first-api-call.md)
