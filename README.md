# The Holloway House — README

Created by Aaron Sermon

---

## What Is This?

The Holloway House is a horror mystery interactive fiction game built in Twine 2 (Harlowe format). You play as someone who has just inherited a Victorian house from their aunt Vera. The house is not empty. Something called Edmund has been living there for decades — and it has been waiting for someone new to arrive.

Your goal is to uncover what Edmund is, find the tools to destroy it, and escape the house alive.

---

## How To Play

### Option 1 — Play directly in your browser

Open either HTML file in any modern web browser (Chrome, Firefox, Safari, Edge). No installation needed. Click the choices on screen to navigate the story. That's it.

### Option 2 — Import into the Twine app

If you want to view and edit the full branching structure:

1. Download the Twine 2 desktop app from twinery.org, or open the browser version at twinery.org/2
2. On the Twine home screen, click Import From File
3. Select the file named holloway_house_twine.html
4. The full story will open in the visual editor, showing all 37 passages as nodes on a map with connecting lines showing every possible route through the game

---

## Files Included

- holloway_house_twine.html — The Twine 2 importable version with images and GIFs
- the_holloway_house.html — The original styled standalone version
- README.md — This file

---

## Game Structure

The game has 37 passages across five main areas of the house, plus a garden and a cellar.

### Areas

- The Gate and Garden — where you arrive. Contains early clues and an opportunity to leave before things get bad.
- The Entrance Hall — the hub of the house. Connects to all other areas.
- The Drawing Room — contains a key item, a vital note from Vera, and the first mirror encounter.
- The Kitchen — leads to the cellar. The trapdoor here requires the brass key to open.
- The Upstairs Landing — connects to four rooms including Vera's bedroom, the guest room, and the nailed door.
- Vera's Bedroom — the most important room. Contains Vera's research and the tools you need to finish the game.
- The Cellar — the final area. This is where the oldest mirror is kept, and where the game ends.

### Inventory

You collect items as you explore. Some items unlock new choices that would not otherwise appear. The key items are:

- Photograph — found in the garden tin box. Background lore.
- Journal Pages — found in the garden trench. Early warning about Edmund.
- Red Key — found on the drawing room mantelpiece. Opens Vera's bedroom.
- Brass Key — hidden behind a crack in the drawing room mirror frame, engraved CELLAR. Opens the cellar trapdoor.
- Hammer — found in Vera's bedroom wardrobe box. Can be used against Edmund but has limited effectiveness on its own.
- Mirror Glass — found in Vera's bedroom wardrobe box. The primary weapon. Required for the best endings.
- Herb Bundle — found on the kitchen windowsill. Flavour item.
- Ryan's Phone and Ryan's Notebook — found in the guest room. Provide additional backstory about a previous investigator who did not make it out.

---

## The Endings

There are eight endings. Some are dead ends, some are escapes, and one is the true ending.

1. The Mirror-Killer — Destroy the cellar mirror using the mirror-glass with your eyes closed. Clean escape.
2. The Glass (True Ending) — Use the mirror-glass against Edmund directly when confronting him. Complete resolution.
3. Blind Strike — Smash the cellar mirror with the hammer without looking. Hard-won escape, mirror barely destroyed.
4. Running — Leave the house without destroying Edmund. You escape. The mirror stays intact.
5. Defenestration — Smash the attic window and use the glass against Edmund in the nailed room. Unconventional ending.
6. In the Glass — Look directly at Edmund in the cellar mirror. You do not leave.
7. Staying — Take Edmund's hand when he offers it. You remain in the house.
8. Leaving — Turn back in the garden before you ever enter. You leave, but nothing is resolved.

---

## Tips

- Explore thoroughly before going to the cellar. The mirror-glass from Vera's bedroom is essential for the best outcomes.
- The brass key is hidden behind the drawing room mirror frame. Examine the mirror closely or smash it first to find it.
- Do not look at Edmund directly. This is both in-world advice from Vera and a literal game mechanic that determines your ending.
- Ryan's notebook in the guest room explains the rules of what Edmund is if you want the full lore before the confrontation.
- The nailed door upstairs can be forced open with the hammer and leads to an early Edmund encounter with its own branching path.
- Vera's bedroom requires the red key, which is on the drawing room mantelpiece. Getting into her room is the single most important thing you can do.

---

## Technical Notes

- Built using Twine 2 Harlowe 3.3.7 format
- Inventory is tracked using a Harlowe array variable called $inventory
- Story flags are tracked using a Harlowe datamap called $flags
- Images load from Unsplash (photos) and Giphy (animated GIFs) — an internet connection is required for these to display, but the game is fully playable without them
- The game has no save system and runs entirely in a single browser session

---

## Credits

Written and designed by Aaron Sermon

Built with Twine 2 — twinery.org
