# RayTracer
Purpose: Implementing ray-casting, raytracing, and shaders. Overall: My project have following elements within a 3D world coordinate system for part A, part B and Part C. 

Part A: Implement RayCast class. Implement the part that loops through each pixel row and column and computes the start of each rcth ray and rcth direction based on perspective projection. To calculate the start point and the vector for each rcth ray, use the values for a camera such that it is located 1/2 meter from the origin at (0, 0, 0.5) and be aimed along the negative z-axis. The viewscreen should be centered at the origin; parallel with the x-y plane, and with sides parallel to the x and y-axes. The height of the viewscreen should be 0.4 m, and its aspect ratio is 5/4. You should use perspective projection. Test by rendering very small images. Once the program is working try a higher resolution of at least 750 x 600 pixels and save this image.

![image](https://github.com/Yijunliulost/RayTracer/blob/master/Capture1.JPG)

Part B: Now, you are going to add shading to your spheres. All of the sphere positions and sizes should be the same as in part A, but now your scene should have two lights. One should be a parallel light source, simulating the sun, as if it were at 60o from the horizontal (the x-z plane), shining into the scene from right to left at 45o from the z-axis. The second should be a point light source, simulating a light bulb, located at (-1, 1, 0.25). Make the sun pale yellow of color (0.8, 0.8, 0.2), and make the light bulb pale blue of color (0.4, 0.4, 0.8). The five spheres should be the same color as in part A, but each should have different material characteristics. Make the red and purple balls completely matte, with no specular. Make the green ball very shiny with a small specular highlight, and very little diffuse. And, make the blue and orange balls intermediate between shiny and matte and with a broad specular highlight. Once you get the program working, experiment with different values for your material characteristics until you get a picture that you think looks interesting.

Part C: Change your initial ray implementation to Orthographic projection when computing the rays. Add a keyboard callback to switch between Perspective (original ray code) Key P or p, and Orthographic in item 4, key O or o.

Result:

Part A:

![image](https://github.com/Yijunliulost/RayTracer/blob/master/Capture2.PNG)

Part B:

![image](https://github.com/Yijunliulost/RayTracer/blob/master/Capture3.PNG)

Part C:

![image](https://github.com/Yijunliulost/RayTracer/blob/master/Capture4.PNG)
