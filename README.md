### Simple Raycaster Maze Game

This is a minimalist first-person maze game built using a basic raycasting engine in vanilla JavaScript. It demonstrates the core principles of a 2.5D rendering technique, similar to early 3D games.

---

### Features

* **First-Person Perspective:** Navigate a maze in a pseudo-3D environment.
* **Simple Rendering:** The walls are rendered using a raycasting algorithm to project 2D map data into a 3D view.
* **Textured Walls:** The walls are textured using an external image URL.
* **Goal-Oriented Gameplay:** Find your way to the exit (`E`) to win the game.
* **Responsive Design:** The game canvas automatically adjusts to different screen sizes.

---

### How to Play

1.  Clone this repository or download the HTML file.
2.  Open the `index.html` file in a web browser.
3.  Use the following controls to navigate the maze:
    * **Move Forward:** `W` or `Up Arrow`
    * **Move Backward:** `S` or `Down Arrow`
    * **Turn Left:** `A` or `Left Arrow`
    * **Turn Right:** `D` or `Right Arrow`

---

### Technical Details

This project is built with:
* **HTML:** For the game structure and controls.
* **CSS:** For basic styling and layout.
* **JavaScript:** The core game logic, including player movement, input handling, and the raycasting rendering loop.

The raycasting engine works by casting a ray for each vertical column of pixels on the screen. It determines the distance to the nearest wall, and then uses that distance to calculate the height of the wall slice to be drawn. A small portion of the wall texture is then drawn to that slice.

---

### Future Improvements

* Add different levels with more complex mazes.
* Implement enemy characters or collectibles.
* Create a simple 2D minimap in the corner to help with navigation.
* Add audio for movement and events.
* Improve the graphics by adding textures for the floor and ceiling.
* Optimize the rendering for better performance on all devices.
