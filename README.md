# Assignment02
print("Hello, world!")
import requests

url = 'https://raw.githubusercontent.com/Rashmikap12/Assignment02/main/hello.py'
response = requests.get(url)
print(response.text)
