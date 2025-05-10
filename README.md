# Random Kanto 25

A browser-based Pokémon battle simulator featuring random Kanto Pokémon at level 25. Battle against AI opponents with authentic moves and battle mechanics.

## Features

- **Random Team Generation**: Each battle features randomly generated teams of 3 Pokémon from the Kanto region
- **Authentic Moves**: Pokémon have real moves from the PokéAPI, learned at level 25 or below
- **Battle Mechanics**:
  - Turn-based combat with speed and priority considerations
  - HP tracking and damage calculation
  - Pokémon switching when fainted
  - Battle animations for attacks and switching
  - Battle log with detailed information

- **Trainer Stats**:
  - Track total battles played
  - Record wins and losses
  - Pokédex of encountered Pokémon
  - Individual Pokémon battle records

## How to Play

1. **Starting a Battle**:
   - The game automatically generates your team of 3 random Kanto Pokémon
   - Each Pokémon comes with 4 moves from their learnset

2. **During Battle**:
   - Select moves for your Pokémon
   - Watch the battle unfold with animations
   - Switch Pokémon when they faint
   - Battle continues until all Pokémon on one team faint

3. **After Battle**:
   - View your battle results
   - Choose to continue with a new battle or quit
   - Check your trainer stats and Pokédex

## Technical Details

- Built with vanilla JavaScript
- Uses the PokéAPI for Pokémon data and moves
- Responsive design that works on desktop browsers
- No external dependencies required

## License

MIT License - See LICENSE file for details
