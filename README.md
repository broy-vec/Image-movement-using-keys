1. **DOMContentLoaded ensures the script runs after the DOM is fully loaded.**
2. **posX and posY store the current position of the image.**
3. **moveSpeed controls how much the image moves with each key press.**
4. **jumpHeight controls how high the image jumps.**
5. **updatePosition updates the image's position on the screen.**
6. **handleKeyDown handles key presses for movement and jumping.**

**Initial Positioning:**

7. `let posX = window.innerWidth / 2;`: Sets the initial X position of the image to the center of the viewport width.
8. `let posY = window.innerHeight / 2;`: Sets the initial Y position of the image to the center of the viewport height.
9. `let isJumping = false;`: A flag to check if the image is currently jumping.

**Movement and Jumping Constants:**

10. `const moveSpeed = 10;`: Defines the speed at which the image moves in pixels.
11. `const jumpHeight = 50;`: Defines the height of the jump in pixels.
