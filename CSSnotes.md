# How to add gradient background 

## Linear Gradient
**.linear-gradient {
  background-image: linear-gradient(direction, color-stop1, color-stop2);
}**

_Example_
> .linear-gradient {
  background-image: linear-gradient(to right, #ff8a00, #e52e71);
}

## Radial Gradient
**.radial-gradient {
  background-image: radial-gradient(shape size at position, color-stop1, color-stop2);
}**

_Example_
> .radial-gradient {
  background-image: radial-gradient(circle at top right, #ff8a00, #e52e71);
}

## Conic Gradient
**.conic-gradient {
  background-image: conic-gradient(from angle at position, color-stop1, color-stop2);
}**

_Example_
> .conic-gradient {
  background-image: conic-gradient(from 0deg at center, #ff8a00, #e52e71);
}

# Insert image
**1. First, make sure you have the image file you want to use in the same directory as your CSS file.**

**2.In your CSS file, select the element to which you want to add the image. For example, if you want to add the image as a background for the body element, you would write**

> body { background-image: url("image.jpg") }

**3. If you want to control the size, position, and repetition of the background image, you can use additional properties such as background-size, background-position, and background-repeat. For example:**

> body { background-image: url("image.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

