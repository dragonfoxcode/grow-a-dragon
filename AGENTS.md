# Grow a Dragon: maintainer note

Game file: `grow-a-dragon.html`. Read this before changing anything.

This game shares its shell with the Classroom Timer Template at `../classroom-timer-template` (https://github.com/dowagercode/classroom-timer-template): player profiles, the two clocks, themes, sound, the microphone meter, the session log, settings and session resume. Calm the Cat and Grow a Dragon are sibling games.

- When you make an important change to that shared shell here (a fix or improvement to anything listed above, not mascot-specific content), make the same change in the template's `classroom-timer.html`, and consider whether the sibling game needs it too.
- Do not port mascot-specific work (the art, galleries, care features) or this game's own visual skin. The template keeps a neutral look.
- Storage: the template derives every localStorage key from `GAME_CONFIG.app`. The games use their own older key names, so port the behaviour, not the key names.
- If `../classroom-timer-template` is not checked out next to this repo, tell the user rather than skipping the port silently.
