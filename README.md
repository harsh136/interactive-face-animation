# Animated Character Face

A simple and fun web project showcasing an interactive animated character face built with HTML, CSS, and JavaScript. The character's eyes follow your mouse cursor, it blinks periodically, hops on click, and emits sparkling particles!


## About

This project is a playful demonstration of front-end web development techniques to create a dynamic and engaging visual element.  It's a great example of how to:

*   **Animate using CSS:**  Utilizes CSS animations for blinking and particle effects.
*   **Manipulate DOM with JavaScript:**  Uses JavaScript to make the eyes follow the mouse, trigger blinking and hopping, and create particles dynamically.
*   **Create interactive elements:** Responds to mouse movements and clicks, making the character feel alive.

## Features

*   **Interactive Eye Tracking:** The character's eyes smoothly follow the user's mouse cursor around the screen.
*   **Realistic Blinking:** The character blinks its eyes at random intervals, sometimes even double-blinking for added realism.
*   **Click to Hop:** Clicking on the character's face makes it playfully hop up and down.
*   **Sparkling Particles:**  Randomly generates and emits small, sparkling particles around the face for a touch of magic.
*   **Clean and Minimalist Design:**  The code is designed to be relatively simple and easy to understand, making it suitable for learning and experimentation.
*   **Responsive (to a degree):** While not fully responsive in terms of layout, the character scales reasonably well on different screen sizes due to the viewport meta tag.

## How to Use/Run

1.  **Clone or Download:**  Clone this repository to your local machine or download the `index.html` file.
2.  **Open in Browser:** Simply open the `index.html` file in any web browser (Chrome, Firefox, Safari, Edge, etc.).
3.  **Interact:** Move your mouse cursor around the browser window to see the eyes follow. Click on the character's face to make it hop. Observe the blinking and particle effects.

## Code Structure

The project consists of a single HTML file (`index.html`) that contains:

*   **HTML Structure:**  Sets up the basic elements: `div` for the face, eyes, and particle containers.
*   **CSS Styling:**  Defines the visual appearance of the character, including shapes, colors, animations, and layout.  CSS keyframes are used for animations.
*   **JavaScript Logic:**  Handles the interactivity:
    *   `followCursor()`: Calculates mouse position and updates eye positions.
    *   `blink()` and `startBlinking()`: Manages eye blinking animation with intervals.
    *   `hop()`:  Animates the face hopping on click.
    *   `createParticle()`: Generates and animates sparkling particles.

## Customization

Feel free to experiment and customize this project! You can try:

*   **Changing Colors:** Modify the CSS color values to alter the character's appearance.
*   **Adjusting Animations:**  Tweak the CSS animation properties (duration, timing function) to change the speed and style of animations.
*   **Adding More Features:**  Extend the character's behavior, perhaps adding mouth movements, different expressions, or reactions to other events.
*   **Improving Styling:** Enhance the visual design, maybe adding more detail to the face or background.

## Technologies Used

*   **HTML5:** For structuring the web page content.
*   **CSS3:** For styling and animations.
*   **JavaScript:** For interactivity and dynamic behavior.

## Author

Harsh Vardhan Vishwakarma

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

---

Enjoy playing with the animated character! ✨
