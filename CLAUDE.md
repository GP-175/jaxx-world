{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Jaxx's BlockVenture\
\
A browser-based Minecraft-like voxel game built incrementally for my 6-9 year old son Jaxx. I have zero coding experience \'97 Claude Code does the actual coding.\
\
## Project tracker\
All milestones and tasks are in Linear. The project is "Jaxx's BlockVenture" under team "JayPee". Issues are JP-28 through JP-70. Always check Linear before starting a task.\
\
## Tech stack (locked)\
- Single `game.html` file with HTML + vanilla JS + CSS\
- Three.js 0.160.0 from CDN via importmap \'97 pinned, never @latest\
- localStorage for persistence (M4+ only)\
- HTML5 audio for SFX\
- No frameworks. No build tools. No npm. No package.json.\
\
## Working conventions (read before every task)\
1. One Linear issue per change. Don't bundle.\
2. Always produce a complete, working `game.html` \'97 never diffs unless I ask\
3. Explain in plain English what changed and why. I am a non-coder.\
4. List your assumptions\
5. End with test steps: what to click, what to look for\
6. Surface refactors before doing them\
7. Keep dependencies minimal\
8. Pin all CDN versions\
9. Never add: multiplayer, mobs, hunger, combat, failure states, pitch-black night, scary content, open text inputs that load arbitrary content\
10. Test for child-safety regressions: no loud sounds, no flashing, no anything that could startle a 6-9 year old\
\
## File workflow\
- Working file: `game.html`\
- After completing a milestone, copy to `game-vN-<milestone>.html` (e.g., `game-v1-foundation.html`)\
- Keep all release files. They're the rollback safety net.\
\
## Personalization\
- Child's name: Jaxx\
- Game name: Jaxx's BlockVenture (placeholder, may rename)\
- Favorite themes: TBD \'97 ask before M5\
- Favorite color: TBD \'97 ask before M5\
\
## Where to start\
First task is **JP-28: [M1-T1] Project skeleton**. Then proceed in order: M1 \uc0\u8594  M2 \u8594  M3...\
\
## When unsure\
Ask me before generating 200 lines I didn't want. One quick question is always cheaper than a wasted output.}