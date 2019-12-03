# Videojuegos-Final Project
### Large-Scale Realistic Cloud Rendering Based On Game Engine 
This paper combines different techniques to rendering clouds for both large-scale and short-scale. 
- Perlin Noise: Creates 4 layers with different level of detail of noise. After that, Perlin requires mix them all and that´s how we can obtain a texture for realistic clouds.
- In order to simulate light passing through the clouds, the paper proposes use Raymarching technique. This technique tracks the light into a cube, lengthens the ray, and detects if the current ray casts on the inner cloud.

The results obtained are:
![cube with the clouds](http://https://github.com/sergiorvs/Videojuegos-Final/blob/master/screenshoots/Captura.PNG) 

 Locating a cube on the scene
![cube with the clouds](http://https://github.com/sergiorvs/Videojuegos-Final/blob/master/screenshoots/Cubo.PNG) 

Reference:
[1] Hu, W., Luo, Y., & Zhang, B. (2018, June). Large-scale realistic cloud rendering based on game engine. In 2018 IEEE/ACIS 17th International Conference on Computer and Information Science (ICIS) (pp. 1-6). IEEE.
