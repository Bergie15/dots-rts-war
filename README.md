# Dots RTS War

A minimalist real-time strategy game in one HTML file. Blue dots against red dots, fought over bases, a river and two bridges.

Open `index.html` in any browser (phone or desktop). No build step.

## How to play
- Each side has a headquarters and a town; two neutral outposts sit by the river.
- A light runs around each of your bases. When it closes the ring, a new **blue unit** steps out (every 8–13 seconds, up to 14 units per army).
- **Drag a unit** and draw a path. Only the unit under your finger moves, along your line.
- End the path on a base to **capture** it (gray number = its defense), or anywhere to hold ground.
- Or **tap a unit, then tap where it should go**. It takes the quickest route.
- Dots have 3 health and **shoot** the nearest enemy in range, stopping to fight. Dots that stand still **dig in** (gold shield) and take half damage.
- Every third unit from your HQ is a **tank**: slow, 8 health, double damage and longer range.
- **Fog of war**: you only see what your units and bases can see; enemy dots outside that stay hidden. A dark **front line** marks where the armies meet.
- **Terrain**: rivers and ponds slow units (and they can't dig in while wading), grey mountains block movement, and raised **hills** give +20% range and 25% less damage taken (white chevron).
- **AIRSTRIKE** bombs an area after a short delay. **SUPPLY +3** drops 3 units at one of your bases.

Win by wiping out the red army, or by holding more bases when the 3:00 clock runs out (dot count breaks ties). Three enemy commanders: Recruit, Captain, General.
