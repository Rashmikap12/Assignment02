# Assignment02
print("Hello, world!")
import requests

url = 'https://raw.githubusercontent.com/yourusername/Assignment02/main/hello.py'
response = requests.get(url)
print(response.text)
