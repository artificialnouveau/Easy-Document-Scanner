# Easy-Document-Scanner
Developed a simple function that detects and rotates documents so that it can be viewed from a bird's eye view.

This can be achieved in three easy steps:

    Edge Detection
    Contour Detection
    Four point transformation

Edge Detection is commonly used to identify and understand objects in an image. It is useful in cases when all the intricate details of an image are not needed, but rather only when you need the overall shape. Edge detection provides information where image intensity changes drastically. It may or may not form a closed shape.

Contours are defined as refined boundaries of objects and can be really helpful in detecting objects.

Four point transformation is used to obtain a top-down, “birds eye view” of an image. It is a bijection (one-to-one correspondence) that maps lines to lines, and thus a collineation.
