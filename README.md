# Melodic Isles: Nightfall Resonance

Melodic Isles is an original browser creature-music collection game inspired by the structure of ensemble-building games. The progression loop uses breeding, real-time incubation, feeding, island bed limits, collecting, limited events, late-game attunement, and monsters whose visible body mechanics explain the sounds they perform. All creature names, island names, vector art, UI, code, progression values, sound synthesis, and musical arrangements in this repository are original. No My Singing Monsters or Tower Battles audio, art, models, source code, or extracted assets are included.

## GitHub Pages

Upload every file from the ZIP directly into the root of one GitHub repository. There are intentionally no folders. In GitHub, enable Pages from the main branch and repository root.

## World and collection

- 8 full islands: Verdant Groove, Frostbell Atoll, Ember Circuit, Moonlit Reverie, Tideglass Reef, Bramble Brassworks, Gloamforge Hollow, and Starfall Bastion.
- 2 late-game Islets: Prism Hand Islet and Null Crown Islet.
- 105 original species and 420 collection form slots.
- Common, Rare, Epic, and Legendary forms. Rare and Epic rendering changes silhouette geometry and appendages in addition to changing color treatment.
- 6 limited Seasonals with event-specific breeding combinations.
- Island Titans, two Islet Primordials, and the Grand Resonator world construct.

## Nightfall expansion systems

- Nightfall Masquerade is active from October 1 through November 3 and enables Gourdhowl and Candlejaw.
- Resonance Week is active from October 8 through October 18 and boosts late-game rarity odds and performance Music Notes.
- The Events screen calculates live remaining time from the player's current date.
- Additional annual event windows include Frosttide, Heartwake, Bloomrise, and Sunflare.
- Grand Resonator is purchased dormant, then powered by permanently boxing one required monster from each of the 8 main islands. Powering it is also required for Null Crown Islet.
- Islets use attunement rather than ordinary breeding: raise the listed source monster to level 15 and transform it into its Islet performer.
- Islet Primordials require the rest of that Islet's attuned roster before awakening.

## Music and performance animation

Every island has its own tempo, tonal mode, arrangement behavior, and performer roster. The browser synthesizes percussion, plucks, bells, brass, organs, vocal-like formants, noise percussion, bass impacts, and distorted leads through Web Audio with compression and reverb. Songs evolve through 8 phrases instead of looping one unchanged bar.

Performers no longer use a universal idle bounce as their sound animation. Their sound rig activates only when their musical part fires. Depending on the creature, jaws clamp, mouths form vowels, arms strike drum surfaces, bodies stomp, bellows compress, horn structures flare, strings are plucked, orbiting plates collide, or wings snap open.

Null Crown Islet is the hardest destination and uses the most aggressive arrangement: 150 BPM, Phrygian pitch material, heavy impact percussion, dark organ layers, choir, brass, distorted lead, escalating later phrases, and a Primordial finale. Its composition is original and does not copy any external boss theme.

## Core progression

- Two-parent breeding on main islands with level-4 breeder requirements.
- Unique limited Seasonal combinations during their event windows.
- Real timestamp incubation with an absolute 60-minute maximum.
- Monster feeding to level 20.
- Castle bed capacity and upgrades.
- Decoration income boosts and Harmony Boost timers.
- Up to 12 hours of offline monster coin accumulation.
- Permanent island Star mastery.
- 25 main quests plus rotating progression goals.
- Daily reward, XP, levels, collection milestones, Music Notes, Stars, Coins, and Gems.
- Local autosave plus save-code export/import.
- Reusable development button for +3,000 Gems with a 0.1-second cooldown.
- Music and SFX controls from 0% to 2000%.
- Responsive iPad/iPhone and desktop layouts.
- Installable PWA and service-worker offline cache.
- No CDNs or external runtime dependencies.
- No in-game emojis.

## Testing

Five PNG screenshots in the repository are fresh captures of this exact upgraded code running in headless Chromium. QA renders all 10 destinations, starts a performance on every destination, opens all major screens, checks current event visibility, validates structural Rare/Epic artwork differences, validates all JavaScript syntax, and checks for page errors.

## Repository layout

The repository is intentionally flat. Core files include `index.html`, `style.css`, `catalog.js`, `monster-art.js`, `events.js`, `save-tools.js`, `audio-engine.js`, `game.js`, `pwa.js`, `sw.js`, `manifest.webmanifest`, app icons, original WAV interface sounds, five QA screenshots, research notes, and the test report.
