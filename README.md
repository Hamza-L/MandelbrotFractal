# MandelbrotFractal
A graphics program that generates a mandelbrot fractal. It is mostly shader code.

<img src="https://github.com/Hamza-L/MandelbrotFractal/blob/master/Mandel1.png?raw=true" alt="Mandelbrot1" width="1100"/>

<img src="https://github.com/Hamza-L/MandelbrotFractal/blob/master/Mandel2.png?raw=true" alt="Mandelbrot2" width="1100"/>

## How it works!
It makes use of this very simple and elegant iterative function

>z = z*z + c

*with the first iteration being at z=0*

Depending on how many iterations are needed before the function diverges to infinity, the individual pixel is assigned a colour. Black is assigned if the function converges or is stable. This simple algorithm leads to beautiful fractal pattern.

## Dependencies:
- glfw (window)
- Vulkan (graphics api)
- glm (math library)