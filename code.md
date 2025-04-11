---
layout: default
---

My educational background is in software development, though I've had fewer opportunities to use it while working in QA.
[You can view my GitHub page through this link](https://github.com/Nevakanezah)

## HorseEnhancer

<iframe width="560" height="315" src="https://www.youtube.com/embed/0o2M9TfdNFk?si=1JnYUK-JCRtXwj7d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Minecraft communities I'd been a part of were no strangers to the technical limitations of the game's creative platform. One of the more common examples
was the horse breeding system, which aggressively selects for perfectly average offspring. Dedicated players seeking the "perfect" horse have to endure hundreds of generations of breeding
in pursuit of microscopic odds. I originally wrote the plugin in Java, though it has since been rewritten in Kotlin by my friend CLESurrealism.

HorseEnhancer is a [Spigot plugin](https://www.spigotmc.org/resources/horseenhancer-2-0-mc-1-18.75692/) that implements the following changes:

*   A more deterministic breeding calculation that produces children resembling their parents
*   Horse genders and gelding, enabling control of bloodlines
*   Horse inspection and unique identification, including parentage info
*   Horse management commands
*   Inbreeding prevention

## Texylvania

One of my game jam submissions, [Texylvania](https://nevakanezah.itch.io/texylvania) is a 2d shooter written in Godot where you play a vampire that has escaped to the wild west. To whit:

> The old country is overrun with these goddamned vampire hunters, 
> so we're going where there's no silver or holy water: 1800s America! 
> Thank goodness they have these enormous hats to handle all these high noons.

The sun is the only lethal threat in the game however bullets damage your hat, increasing the damage taken while standing in sunlight.

The movement & shooting code, as well as terrain object population was created by MrCowDisease. I designed the gameplay loop, as well as creating the rest of the game's code.
This includes:

*   Entity & player health
*   Projectile behaviour
*   Music & Sound effect implementation
*   User interface
*   Start screen
*   day/night cycle, and object shadows


## Point Patron

My Tabletop simulator mods often involve a modicum of LUA code for various UI functionality.
The most involved example of this is the "Point Patron" - A spawnable object that creates an onscreen HUD for displaying player scores, intended for streaming tournament games.

<iframe width="560" height="315" src="https://www.youtube.com/embed/vZ8SOhD_cCg?si=o_HdTaqiD43tGs_n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The UI supports incrementing/decrementing score, multiple players, toggling alternate win conditions, and moving/unlocking the UI. 
All interactions are handled manually.

[back](./)
