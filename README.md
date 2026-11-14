# 🍌 Minx's Banana Jump

An 8-bit, kid-friendly jungle platform game built with Finbar.

Help **Minx the monkey** jump across platforms, collect bananas, and reach the golden tree.

## How to play

Just open `index.html` in any web browser — no build step, no downloads, nothing to install.

Minx **runs forward all by himself** — there's just **one key** to learn:

- **Jump:** SPACE (or click / tap the game — on phones/tablets there's one big TAP TO JUMP button)
- **Grab a vine (Level 2):** jump toward it — Minx grabs on automatically
- **Let go of a vine:** SPACE again — the same jump button (after letting go, Minx can't grab straight back on for a moment, so letting go really works)
- **Restart the level:** R

Minx runs at a calm, slower speed, and the platforms are wide and spread out, so jumps feel easy. The vines are long — the swing reaches right over the next platform. Behind it all is a full, leafy jungle, and the water is a stony creek with ripples and pebbles.

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

## Made with

Plain HTML, CSS and JavaScript on a `<canvas>` — all the 8-bit art and sounds are drawn/beeped in code, so there are no image or sound files to lose.

## Ideas for next versions

- A counting question at the end of each level ("How many bananas did Minx find?")
- Level 3: gentle moving platforms
- A two-player mode where a friend controls a second monkey
