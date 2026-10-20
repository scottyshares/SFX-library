# Using this SFX library in an editing session

## Philosophy: subtle by default

Sound effects support the video; they are never the main thing the viewer notices.
Done right, they almost happen without the viewer realizing they happened. When in doubt, use fewer, quieter sounds, or none.

- **Keep sounds quieter than the voice.** SFX sit under the voice, never louder. Start around -18 to -24 dB relative to dialogue and never let one mask speech.
- **One sound per moment.** Don't layer several effects on the same beat. A single well-placed sound beats a stack.
- **Don't overwhelm the video.** Leave plenty of moments with no SFX at all; not every cut, caption or zoom needs one.
- **Exception: deliberate emphasis.** A sound can step forward when it matches something big on screen (e.g. a thunder clap during a storm, an impact on a key reveal). Use these sparingly so they keep their punch.

## Finding and placing sounds

- Find sounds in `catalog.csv` (name, category, duration_s, format, path). Pick by category + name; check duration fits the moment.
- Categories: Whooshes/Risers/Transitions (cuts, scene changes, zooms), Booms/Impacts/Horror Tension (reveals, emphasis),
  Pops/Clicks/UI (on-screen text, captions, UI callouts), Comedy and Awkward Pauses, Funny/*, Anime, Gaming/Money, Foley.
- Risers should end exactly on the cut/hit they lead into (place by end time, not start time).
- Copy only the sounds a project uses into that project; reference them by the paths here.
