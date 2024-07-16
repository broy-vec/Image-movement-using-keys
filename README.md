DOMContentLoaded ensures the script runs after the DOM is fully loaded.
posX and posY store the current position of the image.
moveSpeed controls how much the image moves with each key press.
jumpHeight controls how high the image jumps.
updatePosition updates the image's position on the screen.
handleKeyDown handles key presses for movement and jumping.

Initial Positioning:

let posX = window.innerWidth / 2;: Sets the initial X position of the image to the center of the viewport width.
let posY = window.innerHeight / 2;: Sets the initial Y position of the image to the center of the viewport height.
let isJumping = false;: A flag to check if the image is currently jumping.
Movement and Jumping Constants:

const moveSpeed = 10;: Defines the speed at which the image moves in pixels.
const jumpHeight = 50;: Defines the height of the jump in pixels.
