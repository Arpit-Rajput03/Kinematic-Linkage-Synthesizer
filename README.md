# Kinematic-Linkage-Synthesizer

I built this web-based tool to make mechanical linkage synthesis a lot more visual, interactive, and accessible. Instead of wrestling with MATLAB or heavy desktop software, you can solve 4-point and 5-point rigid body synthesis problems right in your browser using real-time geometry and math.

##  What it does

* **Graphical 4-Point & 5-Point Modes:** Click to drop precision points directly onto the canvas. You can tweak sliders for bounding radii, drag ground pivots around, and watch the constraint lines and crank circles update in real time.
* **Analytical Mode:** Prefer the math? Dial in your free-choice parameters (coupler, crank, and follower angles) and let the complex number equations solve for the exact dyads.
* **Live Kinematic Playback:** Once your linkage is synthesized, hit play. The tool animates the four-bar mechanism, traces the full coupler curve, and automatically checks if your design suffers from circuit defects.

##  Built With

* **HTML5 Canvas & CSS3**
* **100% Vanilla JavaScript**
* **Zero Dependencies** (No React, no libraries, just pure browser APIs)

##  How to Run It

Since there's no backend or build step, running this is as easy as it gets:

1. Clone or download this repository.
2. Open `index.html` in your favorite web browser.
3. Start placing points!

##  Quick Controls

* **Pan:** Click and drag anywhere on the background.
* **Zoom:** Scroll your mouse wheel.
* **Auto-Fit:** Click the "Auto Fit ⛶" button to snap your entire linkage and path back into view.

---

*Created by Arpit Singh 
Licensed under MIT.*
