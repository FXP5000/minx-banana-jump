# 🍌 Minx's Banana Jump

An 8-bit, kid-friendly jungle platform game built with Finbar.

Help **Minx the monkey** jump across platforms, collect bananas, and reach the golden tree.

## How to play

Just open `index.html` in any web browser — no build step, no downloads, nothing to install.

## Main menu & shop

Pressing START opens the **main menu** first. Every banana collected in the game also fills your **Banana Bank** (it remembers your total between visits), and the bank buys things in the menu:

- **Common monkeys** — the rainbow colours (Red, Orange, Yellow, Green, Blue, Purple), 10–20 bananas each. Classic brown Minx is free.
- **RARE monkeys** — the ⭐ **Golden** monkey (150 bananas) and the 🌌 **Void** monkey (250 bananas, with glowing purple eyes).
- **Hats & accessories** — Cap, Flower, Party Hat, Shades, Banana Hat and the 👑 Crown (15–100 bananas). Minx wears his hat in the game (he takes it off while swinging on a vine).

Your bank, monkeys and hats are saved, so they are still yours next time you play.

**You control Minx** — he goes where you steer him:

- **Move backwards / forwards:** ◀ ▶ arrow keys (or A / D) — on phones/tablets there are ◀ ▶ buttons
- **Jump:** SPACE (or click / tap the game — and the ⬆ JUMP button on touch screens)
- **Grab a vine (Level 2):** jump toward it — Minx grabs on automatically
- **Let go of a vine:** SPACE again — the same jump button (after letting go, Minx can't grab straight back on for a moment, so letting go really works)
- **Restart the level:** R

The camera follows Minx and only ever scrolls **forward** — it never scrolls back, and Minx can't walk out of the left side of the screen. So once an area has scrolled past, it's gone: the only way back to the start of a level is dying (which restarts the level) or game over.

Minx moves at his original speed, and the platforms are much wider and spread way out, with gentle height steps, so every jump is easy. The vines are long — the swing reaches right over the next platform. Behind it all is a crowded jungle canopy so thick you can't see the sky, and the water is a stony creek with ripples, pebbles, moss — and fallen logs floating in it. Collecting a banana bursts into sparkles, and splashing into the creek makes a proper splash.

Minx has a **running animation** (pumping legs and arms, a little bob) and a **jumping animation** (arms up, legs tucked, "ooh!" face).

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
- **Level 2 — Vine Swings:** One new idea — vines. Like Level 1, the ground is only at the start, so there's no running underneath: platform clusters over the water are linked by vines. Swing gently across each vine gap to the landing platform on the other side, then climb to the golden tree's platform.
- **Level 3 — Tunnel Tree:** A learning level about *timing* — when to jump and when NOT to. Minx runs through a tunnel carved into a giant tree. The tunnel floor has gaps over the creek (jump those!), but thick roots hang from the tunnel roof: jumping under one bonks his head and stops the jump, so the bananas under roots must be collected by running. After the exit, he climbs the outside of the tree to the golden platform in its branches.
- **Level 4 — Endless Run (unlocked by beating Level 3):** No finish line! The jungle generates itself ahead of Minx forever, mixing **all three** level ideas in a repeating pattern: jumping platforms, vine swings, and whole Tunnel Tree sections (with floor gaps to jump and hanging roots not to jump under). Score = bananas × 10 + metres run. A splash sends Minx back to the last platform he stood on; the run ends when his 3 lives run out. The **🏆 high-score bar at the top** fills up as your score climbs toward the best ever, and the best score is remembered between visits.

The game also runs at a locked 60 steps per second, so Minx's speed is exactly the same on every screen — fast-refresh displays used to run him at double speed.

## Made with

Plain HTML, CSS and JavaScript on a `<canvas>` — all the 8-bit art and sounds are drawn/beeped in code, so there are no image or sound files to lose.

## Ideas for next versions

- A counting question at the end of each level ("How many bananas did Minx find?")
- Level 3: gentle moving platforms
- A two-player mode where a friend controls a second monkey
