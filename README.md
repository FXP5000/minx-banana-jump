# 🍌 Minx's Banana Jump

An 8-bit, kid-friendly jungle platform game built with Finbar.

Help **Minx the monkey** jump across platforms, collect bananas, and reach the golden tree.

## How to play

Just open `index.html` in any web browser — no build step, no downloads, nothing to install.

- **Move:** ◀ ▶ arrow keys, or A / D (on phones/tablets, use the on-screen buttons)
- **Jump:** SPACE (or ⬆ / W)
- **Grab a vine (Level 2):** walk into it — Minx grabs on automatically
- **Let go of a vine:** SPACE
- **Restart the level:** R

## The rules (kept simple for kids)

- Minx starts with **3 lives**, shown in the clean **golden-yellow bar** at the top, divided into 3 sections.
- Minx jumps **gently** — high enough for one platform step, never two.
- There's **no running underneath to the finish**: past the starting ground, the levels are water with platforms over it, so the platforms (and vines) are the only way across. The golden tree only counts when Minx reaches it up on its platform.
- Splash into the **water** and Minx loses a life and restarts at the **start of the level he's in** (that level's bananas come back, so nothing double-counts). Lose all 3 lives and he restarts that **same level** with 3 fresh lives — never all the way back to Level 1.
- **Vines swing slowly and gently** — no fast flying.
- Every **3 bananas = 1 extra life** (lives top out at 3, so the bar always tells the truth; at full lives, every 3rd banana gives +30 bonus points instead).
- The game counts with you as you collect: **1! 2! 3!** — a tiny counting lesson tucked into the fun.
- No enemies and nothing scary. The only danger is the water.

## The levels

- **Level 1 — Little Hops:** Just jumping. Flat ground to start, a first platform that's a little hop up, then platforms over the water that gradually get higher and come back down, climbing at the end to the golden tree's platform. Bananas show the way.
- **Level 2 — Vine Swings:** One new idea — vines. Swing gently across the wide water gaps to reach the far side and the bananas floating in the middle.

## Made with

Plain HTML, CSS and JavaScript on a `<canvas>` — all the 8-bit art and sounds are drawn/beeped in code, so there are no image or sound files to lose.

## Ideas for next versions

- A counting question at the end of each level ("How many bananas did Minx find?")
- Level 3: gentle moving platforms
- A two-player mode where a friend controls a second monkey
