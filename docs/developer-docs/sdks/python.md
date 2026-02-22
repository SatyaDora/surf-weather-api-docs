# Python SDK Example

Example using Python requests library.

```python
import requests

url = "https://api.openweathermap.org/data/2.5/weather"

params = {
    "q": "Goa",
    "appid": "YOUR_API_KEY"
}

response = requests.get(url, params=params)
print(response.json())