# Interactive_Login_Page

This code is an HTML, CSS, and JavaScript code that creates a particle motion animation in the background of a website. The animation consists of a canvas element that is created in the HTML code and is styled using CSS. The canvas element is used to draw and animate the particles, which are instances of the Particle class that is defined in the JavaScript code.

The Particle class is used to create particles with random positions, velocities, sizes, and colors. Each particle is drawn as a circle on the canvas, and it moves with a constant velocity in a random direction. When a particle reaches the edge of the canvas, its velocity is reversed so that it bounces back.

The particles also interact with the mouse cursor, creating a repulsive force that makes them move away from the cursor when it gets close to them. This is achieved using the repel method of the Particle class, which calculates the distance between a particle and the mouse cursor and applies a force to the particle that is proportional to the distance.

The animation is created using a loop that updates the position of each particle and redraws it on the canvas at each frame. The loop runs continuously using the requestAnimationFrame method, which is a more efficient way of animating than using setInterval or setTimeout.

In addition to the particle animation, the code also creates a login box using HTML and CSS. The box is positioned in the center of the screen and has a transparent background with a border and a drop shadow. It contains two input fields for the username and password, and a button that is styled to have an animated gradient effect.





