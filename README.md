# Mini Dwarf RTS Game

A simple but fun Real-Time Strategy (RTS) game built with vanilla HTML, CSS, and JavaScript. Manage your dwarven fortress, gather resources, expand your population, and defend against goblin invaders!

### [Play the Game Live!](https://your-username.github.io/your-repo-name/)
*(Replace this link after you enable GitHub Pages in Step 3 below!)*


*(It is highly recommended to replace this with your own screenshot or GIF!)*

---

## How to Play

The goal is to build a thriving fortress and survive the goblin attacks.

-   **Gather Resources:**
    -   **Train Miners (🧑‍⛏️):** They automatically gather **Gold (💰)** from the map. Gold is used to train all types of dwarfs.
    -   **Train Masons (🧑‍🧱):** They automatically gather **Stone (🪨)**. Stone is used to build houses.

-   **Expand Your Fortress:**
    -   **Build Houses (🏠):** Spend Stone to build houses. Each house increases your population capacity by 5, allowing you to train more dwarfs.

-   **Defend Yourself:**
    -   **Train Warriors (⚔️):** These brave dwarfs don't gather resources. Instead, they automatically seek out and attack any **Goblins (👹)** they see.
    -   **Goblins:** Once you train your first warrior, goblins will begin to spawn on the edges of the map and attack your dwarfs. Be prepared!

-   **Game Speed:**
    -   Use the **Speed** button to toggle between normal (1x) and fast (3x) game speed.

---

## Features

-   **Pure JavaScript:** No frameworks or libraries. Just plain HTML, CSS, and JS.
-   **RTS Mechanics:** Classic resource gathering, unit training, and base-building loop.
-   **Simple AI:** All units (dwarfs and goblins) operate automatically based on a state machine (`IDLE`, `HUNTING`, `FIGHTING`, etc.).
-   **Grid-Based Combat:** Units engage in combat when adjacent to enemies.
-   **Responsive Design:** The layout and game grid scale to fit different screen sizes, from mobile to desktop.

## How to Run Locally

1.  Clone or download this repository.
2.  Open the `index.html` file in any modern web browser.

That's it! Enjoy the game.