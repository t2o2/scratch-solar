
# 🌌 **Solar System in Scratch: A Galactic Guide for Kids** 🌌

![demo](https://github.com/t2o2/scratch-solar/blob/942739025757cb0001366848ad1a9f5f03ab9ce8/solar.gif?raw=true)

----------

### **1. Setting Up: 🌠**

-   **Open Scratch:** Launch the Scratch website and kick off a new cosmic project.
-   **Backdrop:** Opt for a dark, mysterious backdrop like "starry night" to set the space mood.

----------

### **2. Crafting the Sun: ☀️**

-   **Choose a Sprite:** Tap on the cat icon (or the 'Choose a Sprite' button) and pick a radiant circle or ball. This will be our mighty sun.
-   **Resize:** Amplify the sun's grandeur by adjusting its size.
-   **Position:** Command the sun to take its rightful place at the center of our universe.

[Sun Code](https://github.com/t2o2/scratch-solar/blob/main/imgs/sun.png?raw=true)

----------

### **3. Deploying the Planets: 🪐**

-   **Choose More Sprites:** For every planet, select a circle or ball sprite.
-   **Resize & Recolor:** Modify each sprite's size to resemble the planets. Use the 'Fill' tool to paint them in their iconic colors (e.g., fiery red for Mars, deep blue for Earth).
-   **Position:** Strategically position each planet sprite around the sun, ensuring they maintain their personal space.

----------

### **4. Setting Planets in Motion: 🌍🔄**

For each planet:

-   **Go to Code Tab:** Select the planet sprite and venture into the 'Code' realm.
-   **Use the 'Forever' Loop:** This magical loop ensures the planet never stops its majestic dance around the sun.
-   **Rotate:** Within the 'Forever' loop, deploy the 'turn' block to set the planet spinning. Tweak the rotation degree to control its speed.
-   **Advance:** Post the 'turn' block, command the planet to march forward in its orbit using the 'move' block.
-   **Pause:** Introduce a 'wait' block to dictate the rhythm of the orbit.

[Earth Code](https://github.com/t2o2/scratch-solar/blob/main/imgs/earth.png?raw=true)

----------


### **5. Introducing Moons (For the Extra Curious!): 🌙**

-   **Sprite & Position:** Choose a smaller circle sprite for the moon and position it near a planet.
    
-   **Variables:** Create `MoonTimer`, `MoonAngle`, and `MoonRadius`. Initialize `MoonTimer` to `0`, `MoonAngle` to `0`, and set `MoonRadius` for desired distance.
    
-   **Orbiting Code:**
    
    -   In the 'Code' tab for the moon:
        -   Use a 'Forever' loop.
        -   Increment `MoonTimer` (e.g., by `0.1`).
        -   Set `MoonAngle` to `MoonTimer x 10`.
        -   Calculate x position: `Planet's X + (MoonRadius x cos(MoonAngle))`.
        -   Calculate y position: `Planet's Y + (MoonRadius x sin(MoonAngle))`.
-   **Test:** Click the green flag to see the moon orbiting its planet.

[Moon Code](https://github.com/t2o2/scratch-solar/blob/main/imgs/moon.png?raw=true)

----------


### **6. Drawing Orbits with the Pen Tool: 🖊️🌌**

-   **Activate the Pen Tool:** For each planet sprite, go to the 'Extensions' at the bottom-left and add the 'Pen' extension.
    
-   **Setup:**
    
    -   At the start (e.g., when the green flag is clicked), use the `pen up` block to ensure the pen is not drawing immediately.
    -   Set the pen's color to match the planet or choose a light gray for a neutral orbit color.
    -   Use the `set pen size to` block to adjust the thickness of the orbit line. A smaller value like `1` or `2` is recommended.
-   **Drawing the Orbit:**
    
    -   Before the planet starts its movement in the 'Forever' loop, use the `pen down` block to start drawing.
    -   As the planet moves, it will now draw its path, visually representing its orbit.
    -   If you want to clear the previous orbits and redraw them, use the `clear` block from the pen extension at the beginning of your script (e.g., when the green flag is clicked).
-   **Test:** Click the green flag to see the planets drawing their orbits around the sun.

[Planet Code](https://github.com/t2o2/scratch-solar/blob/main/imgs/planet.png?raw=true)

----------


### **8. Meteoric Encounters: Sensing, Bouncing & Looping ☄️**

-   **Choose a Sprite for the Meteor:** Opt for a suitable sprite, perhaps a small rock or asteroid-like shape, to represent the meteor.
    
-   **Initial Position & Movement:**
    
    -   Place the meteor at a random position on one edge of the screen.
    -   Use the `pick random` block from the 'Operators' section to set a random starting angle for the meteor's direction (e.g., between 0 and 360 degrees).
    -   Use the `point in direction` block and input the random angle to set its initial direction.
    -   In a 'Forever' loop, use the `move` block to keep the meteor moving.
-   **Sensing & Bouncing:**
    
    -   Inside the 'Forever' loop, add the `if... then` block from the 'Control' section.
    -   From the 'Sensing' section, drag the `touching` block into the `if... then` condition.
    -   Set the `touching` block to detect any planet sprite.
    -   If the meteor is touching a planet, use the `if on edge, bounce` block to make the meteor bounce off in a new direction.
-   **Looping Across the Screen:**
    
    -   Still inside the 'Forever' loop, add another `if... then` condition to check if the meteor is touching the edge using the `touching edge?` block from the 'Sensing' section.
    -   If the meteor touches the edge, reposition it to the opposite edge and set a new random direction using the `pick random` and `point in direction` blocks.
-   **Enhancements (Optional):**
    
    -   You can add sound effects for when the meteor touches a planet.
    -   Introduce a slight rotation to the meteor for a more dynamic appearance using the `turn` block.

----------

### 9. **Testing & Exploration** 🎬

-   Click the green flag to see the celestial dance of planets, moons, and meteors around the sun. Adjust and experiment to make the universe truly your own!

----------

**Remember, young explorer:** The universe is vast, and so is your imagination. Customize your solar system, introduce new elements, or even animate a spaceship zipping through. The cosmos is your playground. **Happy coding and safe space travels!** 🌟🚀
