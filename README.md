
# Enemy and Defender

A python simulation of the hit playground game "Enemy and Defender"

## Basic rules

Each player (P) selects one other player to be their enemy (E) and a different player to be their defender (D). P's goal is to maneuver themself into a position such that D is between P and E. In other words, P is observing the line that is naturally implied by D and E and then positioning themself on that line, on the opposite side of D from E. 

In practice, this forms a chaotic system of players optimizing for themselves which occasionally results in emergent system behavior.

## This simulation

This simulation starts with ten players randomly scattered on a screen with wrap-around edges (e.g., if a player moves too far to the right, they will appear at the same vertical level, on the left edge).

Each player automatically and randomly selects their enemies and defenders.

### Controls

- `spacebar` restarts the simulation, re-picking initial player positions and their enemies and defenders
- `+` increases the number of players. Also restarts positions and enemies/defender selections.
- `-` decreases the number of players. Minimum number is 3. Also restarts positions and enemy/defender selections.
- `n` or `N` changes the color scheme to follow one particular player. Highlights the selected player in blue, their defender in green, and their enemy in red. All other players are black. Pressing `N` again, follows a new player. 
- `q` or `Q` quits the simulation and closes the window.