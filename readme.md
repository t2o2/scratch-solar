
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

----------


### **5. Introducing Moons (For the Extra Curious!): 🌙**

-   **Sprite & Position:** Choose a smaller circle sprite for the moon and position it near a planet.
    
-   **Variables:** Create `Moon_Timer`, `Moon_Angle`, and `Moon_Radius`. Initialize `Moon_Timer` to `0`, `Moon_Angle` to `0`, and set `Moon_Radius` for desired distance.
    
-   **Orbiting Code:**
    
    -   In the 'Code' tab for the moon:
        -   Use a 'Forever' loop.
        -   Increment `Moon_Timer` (e.g., by `0.1`).
        -   Set `Moon_Angle` to `Moon_Timer x 10`.
        -   Calculate x position: `Planet's X + (Moon_Radius x cos(Moon_Angle))`.
        -   Calculate y position: `Planet's Y + (Moon_Radius x sin(Moon_Angle))`.
-   **Test:** Click the green flag to see the moon orbiting its planet.

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

----------

### **7. Bringing the Universe to Life: 🎬**

-   **Green Flag:** Hit the green flag and watch in awe as the planets commence their eternal waltz around the sun. Fine-tune the 'turn' and 'wait' blocks if you wish to alter their dance moves.

----------

### **8. Chronicle & Broadcast: 📜📡**

-   **Document Your Creation:** Bestow a title upon your solar system masterpiece and save it for posterity.
-   **Broadcast:** Share your cosmic creation with fellow space enthusiasts, friends, family, or the vast Scratch cosmos.

----------

### **🚀 Tips & Tricks for Young Astronomers 🚀**

-   **Size Matters:** The planetary sizes in this project aren't true to scale. Dive into some research to discover the actual sizes and adjust accordingly.
-   **Detailing:** Elevate your universe by adding intricate details like asteroid belts, shooting comets, or even the mesmerizing Milky Way.

----------

**Remember, young explorer:** The universe is vast, and so is your imagination. Customize your solar system, introduce new elements, or even animate a spaceship zipping through. The cosmos is your playground. **Happy coding and safe space travels!** 🌟🚀
