## Example Code

This snippet demonstrates how to fetch current weather data for Goa using the Python `requests` library.

```python
import requests

url = "https://api.openweathermap.org/data/2.5/weather"
params = {
    "q": "Goa",
    "appid": "{your_api_key}"
}

response = requests.get(url, params=params)
print(response.json())
```