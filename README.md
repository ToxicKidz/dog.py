An API wrapper for [`thedogapi`](https://thedogapi.com/) that covers the full API.

To install, just run this command:
```
pip install -U dog.py
```

Here's an example for getting an image and printing its url:

```
from dog import Client

client = Client('my_api_key_here')

image = client.get_images()[0]

print('Here is the Dog Image link:', image.url)
```
