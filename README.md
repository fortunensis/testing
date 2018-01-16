# testing
from PIL import Image
im = Image.open("testi.jpg")
im.save("testi_2.jpg",optimize=True,quality=20)
