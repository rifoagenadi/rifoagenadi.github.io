# Sound Effects for Poop Gashapon

This directory should contain the following sound effect files:

## Required Sound Files

### 1. shake.mp3
- **When it plays**: During the capsule shaking animation (1 second)
- **Suggested sounds**: Shaking/rattling sound, maraca sound, dice rolling
- **Free sources**:
  - [Freesound.org](https://freesound.org/) - Search "shake", "rattle", "maraca"
  - [Zapsplat.com](https://www.zapsplat.com/) - Search "shake", "rattle"
  - [Mixkit.co](https://mixkit.co/free-sound-effects/) - Browse sound effects

### 2. henshin.mp3
- **When it plays**: When the capsule pops and the poop is revealed
- **Suggested sounds**: Kamen Rider Birth henshin sound, transformation sound, magical reveal
- **Free sources**:
  - Search YouTube for "Kamen Rider Birth henshin sound" and download/convert
  - [Freesound.org](https://freesound.org/) - Search "transformation", "power up", "reveal"
  - [Zapsplat.com](https://www.zapsplat.com/) - Search "transformation", "magic"

## How to Add Sounds

1. Download your chosen sound effects (MP3 format)
2. Name them exactly as:
   - `shake.mp3`
   - `henshin.mp3`
3. Place them in this `sounds/` directory

## Note on Browser Autoplay Policy

Some browsers block audio autoplay. If sounds don't play, users may need to interact with the page first (like clicking anywhere) before the sounds can play. The code already handles this gracefully.

## Testing

After adding the sound files, open `poop.html` in a browser and click the "Roll the Capsule!" button. You should hear:
1. Shake sound during the 1-second shake animation
2. Henshin/reveal sound when the capsule pops

