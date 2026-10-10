# Horde Breaker — by Zaib

A top-down, twin-stick zombie survival shooter for mobile browsers. Move with the left stick and aim with the right one, and your gun fires on its own while you aim. Survive five cursed maps, build up kill streaks and take down the bosses.

**Play:** https://wahidzeb.github.io/horde-breaker/

![Gameplay](screenshot.png)

## Features
- **Campaign:** 5 maps and 20 levels: Suburbia, Dead Mall, St. Mercy Hospital, Fort Ashfall and Night City (rain and lightning). There are wave, timed-survival and boss levels. Each level has 3 stars and objectives such as finishing with high health, hitting a streak, getting explosion kills or keeping your accuracy up.
- **Endless survival:** play on any map. A boss arrives every 5 waves, and your best wave and score are saved for each map.
- **Zombies:** walkers, runners, brutes (with a telegraphed charge), acid spitters, exploding bloaters, lunging crawlers, and 5 named bosses that charge, slam, spit volleys and summon minions. The last few zombies of a wave go into a frenzy.
- **8 weapons:** pistol, shotgun, SMG, assault rifle, sniper (pierces), flamethrower, grenade launcher and minigun. Each has its own ammo and reload, and each can be upgraded for damage, fire rate, magazine size and reload speed. You also get grenades, a deployable auto-turret and a dash with brief invulnerability.
- **Pickups:** ammo, health, grenades, double damage, speed, invincibility, nuke and coins. Explosive barrels are placed around the maps.
- **Armory:** buy, upgrade and equip a 3-weapon loadout. Survivor upgrades cover max HP, armor, move speed, grenade capacity, turret and scavenger luck.
- **Polish:** dynamic lighting with a flashlight cone, glowing zombie eyes, muzzle flashes, cartoon goo (no gore), scorch marks, screen shake, hit flashes, particles, kill-streak multipliers and multi-kill callouts. The title screen shows an animated live demo.
- **Audio:** all sound effects and music are generated with WebAudio. Groans are positional, and the music gets more intense as the horde grows. Bosses have their own theme.
- **Settings:** sound, music, vibration, screen shake, aim mode (Manual / Assist / Auto), joystick type (Floating / Fixed), left-handed layout, graphics (Auto / High / Low) and reset progress.

## Controls
| Action | Touch | Keyboard / mouse |
|---|---|---|
| Move | Left joystick | WASD / arrow keys |
| Aim + fire | Right joystick (fires automatically) | Mouse (hold the left button to fire) |
| Dash | Dash button | Space / Shift |
| Grenade | Grenade button | G / right-click |
| Turret | Turret button | E / F |
| Reload | Reload button | R |
| Switch weapon | Tap the weapon panel | Q / Tab / 1–3 / mouse wheel |
| Pause | Pause button | P / Esc |

## Tech
- One self-contained `index.html` (Canvas 2D + vanilla JS) with no external assets.
- Mobile-first: fullscreen, works in portrait and landscape, supports multi-touch, blocks scrolling and zooming, and respects safe areas.
- Uses delta-time updates and lowers graphics quality automatically if the frame rate drops. The game pauses when the tab is hidden.
- Progress is saved in `localStorage`.

Game by **Zaib**.
