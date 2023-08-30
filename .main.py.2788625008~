from PIL import Image
import requests
from io import BytesIO
x=input("Enter the image URL:")
r=requests.get(x)
i=Image.open(BytesIO(r.content))
with open("img.jpg","wb") as f:
  i.save(f)
