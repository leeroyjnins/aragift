# Birthday Gift Website 🎁

A special interactive website with a gift box landing page and animated GIF character!

## Features

### Landing Page
- Animated gift box in the center with floating animation
- Click to open animation
- Confetti celebration falling from the top
- Congratulation sound (optional)
- Fast transition to the game

### Interactive Character
- Custom GIF character using:
  - `yeet_stand.gif` - idle animation (loops continuously)
  - `yeet_this.gif` - action animation (plays when triggered)
- **Swipe up** (mobile) or **click** (desktop) on the character to trigger the action
- Particle effects
- **Auto-resets** back to idle animation after 1.5 seconds

## Setup

### Adding Congratulation Sound (Optional)
To add a congratulation sound when opening the gift box:

1. Find a congratulation sound effect (MP3 format recommended)
2. Save it as `congrats.mp3` in the same folder as `index.html`
3. The sound will automatically play when the gift box is opened

You can download free sound effects from:
- [Freesound.org](https://freesound.org/)
- [Zapsplat.com](https://www.zapsplat.com/)
- Search for: "celebration", "congratulations", "party horn", "applause"

### Files Required
- `index.html` - Main website file ✅
- `yeet_stand.gif` - Idle animation ✅
- `yeet_this.gif` - Action animation ✅
- `congrats.mp3` - Congratulation sound (optional)

## How to Use

1. Open `index.html` in a web browser
2. Click on the gift box
3. Watch the confetti and enjoy the sound!
4. After the transition, **swipe up** (mobile) or **click** (desktop) on the character
5. Wait 1.5 seconds and it will auto-reset - interact again to repeat!

## Browser Compatibility

Works best on:
- Chrome/Edge (Desktop & Mobile)
- Safari (Desktop & Mobile)
- Firefox (Desktop & Mobile)

## Customization

### Change Colors
Edit the CSS gradients in `index.html`:
- Gift box: Search for `#ff6b9d` and `#c24d7d`
- Background: Search for `#667eea` and `#764ba2`

### Change GIFs
Replace `yeet_stand.gif` and `yeet_this.gif` with your own GIF files (keep the same names)

### Adjust Timing
In the JavaScript section:
- Confetti duration: Change `5000` (5 seconds)
- Landing page transition: Change `800` (0.8 seconds)
- Auto-reset delay: Change `1500` (1.5 seconds) in the `triggerAnimation` function

Enjoy! 🎉
