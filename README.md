- 👋 Hi, I’m @HezronKG
- 👀 I’m interested in python programming
- 🌱 I’m currently learning random python short codes
- 💞️ I’m looking to collaborate on python back end and front end developers
- 📫 How to reach me through my account or email kiongogatune@gmail.com

<!---
HezronKG/HezronKG is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


class shape:
def __init__(self):
self.__areaValue = 0
self.__perimeterValue = 0
def area(self):
print("Area ", self.__areaValue)
def perimeter(self):
print("Perimeter ", self.__areaValue)
class rectangle(shape):
def __init__(self, length, breadth):
shape.__init__(self)
self.__length = length
self.__breadth = breadth
def area (self):
self.__areaValue = self.__length * self.__breadth
print("Area ", self.__areaValue)
class circle(shape):
def __init__(self, radius):
shape.__init__(self)
self.__radius = radius
def area (self):
self.__areaValue = self.__radius * self.__radius * 3.142
print("Area ", self.__areaValue)
myCircle = circle(20)
myCircle.area()
myRectangle = rectangle (10,17)
myRectangle.area()
