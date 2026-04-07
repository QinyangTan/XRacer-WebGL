# XRacer WebGL

XRacer is a fast-paced sci-fi tunnel runner built in Unity and published as a browser-playable WebGL game.

## Play Online

Play the latest public build here:

[https://qinyangtan.github.io/XRacer-WebGL/](https://qinyangtan.github.io/XRacer-WebGL/)

## How To Play

### Core Controls

- `A / D` or `Left / Right Arrow`: steer the drone horizontally
- `Space`: pause or resume the run
- `M` on the main menu: switch between `Hunter Chase` and `Endurance Run`

### Hunter Chase Controls

- `J`: rapid-fire blaster shots
- `K`: homing missile with a 10 second cooldown

## Game Modes

### Hunter Chase

Chase down a randomly selected enemy drone. The target flies ahead of the player, dodges obstacles, and can be destroyed with blaster fire or a missile. Destroying the enemy awards a victory and bonus credits.

### Endurance Run

Classic endless run mode. Survive as long as possible, dodge incoming obstacles, and push for a new distance record.

## Credits And Store

- Collect credits during runs
- Winning `Hunter Chase` grants an extra `500` credits
- Spend credits on unlockable ship variants in the in-game store

## Updating The Website

The web build is hosted on GitHub Pages, so it stays online even when Unity is closed.

To publish a new build:

1. Open the Unity project
2. Run `XRacer > Build WebGL`
3. From the project root, run:

```bash
python3 publish_github_pages.py
```

That command updates the GitHub Pages repository with the newest build and refreshes the website assets.
