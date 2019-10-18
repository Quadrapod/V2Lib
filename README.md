# V2Lib
A vector library with simple functionality to simplify making games in Else Heart.Break()
A V2 represents an array with two elements representing cartesian coordinates.

V2 V2(number x, number y)
  Equivilant to [x,y], only exists for syntactic cleanliness.

V2 V2Rotate(V2 vector, number theta) 
  Rotates a vector by a given angle in radians. Equivilant to multiplying by the rotation matrix.

V2 V2Mul(V2 vector1, V2 vector2)
  Multiplies the x and y components of two vectors.
  
V2 V2Div(V2 vector1, V2 vector2)
  Divides the x and y components of two vectors.
  
V2 VAdd(V2 vector1, V2 vector2)
  Adds the x and y components of two vectors.
  
V2 V2Mul(V2 vector1, V2 vector2)
  Subtracts the x and y components of two vectors.
  
number V2Distance(V2 vector1, V2 vector2)
  Returns the distance between two given vectors.  Very slow.
  
number V2Magnitude(V2 vector1, V2 vector2)
  Returns the magnitude of a give vector.  Very slow.

number V2FromPolar(number angle, number magnitude)
  Returns a cartesian vector from a euler vector.
  
number RandomAngle()
  Returns a random number between 0 and 2pi
  
bool InRadius(V2 point1, V2 point2, number radius)
  Fast check on whether a given point is within a certain radius of another.
  
void DrawVector(array<v2> model, V2 position, number scale, number rotation)
  draws a model given as an array of V2s at a given position on the screen with a given rotation and scale.
