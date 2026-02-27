# Joel Karikkandathil — Mr. Robot Portfolio

A hacker-terminal themed portfolio with authentic Mr. Robot aesthetic: boot sequence, matrix rain, custom cursor, glitch effects, and full terminal styling.

## Features

**Mr. Robot Authentic:**
- Boot sequence with system initialization animation
- Matrix rain background (Canvas, low opacity)
- Custom cursor with smooth lag effect
- CRT scanlines + noise overlay
- Glitch animations on interactive elements
- Terminal-styled sections with command prompts
- fsociety easter eggs + quotes

**Technical:**
- Single-file HTML with embedded CSS/JavaScript
- Responsive (mobile menu included)
- Smooth scroll navigation
- Scroll-reveal animations
- All content from resume integrated

## File Structure

```
portfolio-mrrobot/
├── index.html    # Complete single-file portfolio (HTML + CSS + JS)
└── README.md     # This file
```

## Usage

1. Open `index.html` in any modern browser
2. Watch the boot sequence load
3. Scroll through sections: Hero → About → Skills → Work → Projects → Contact
4. Hover over elements for glitch effects + cursor interactions

## Theme Colors

The palette mirrors the show:
```
--green: #00ff41        // Terminal primary
--green-dim: #00cc33    // Terminal secondary
--red: #ff2222          // Alerts / errors
--amber: #ffb000        // Warnings
--bg: #0a0a0a           // Background primary
--panel: #0f1a0f        // Terminal windows
--border: #1a3a1a       // UI borders
--text: #b0ffb0         // Text primary
--text-dim: #4a7a4a     // Text secondary
```

## Sections

1. **Hero** — Boot animation, glitchy name, terminal prompt, badges
2. **About** — Terminal window with `profile.json` + `mission.txt` output
3. **Skills** — Arsenal cards with progress bars, tech tags
4. **Work** — Timeline with experience (DCKAP, Freelance, GDSC)
5. **Projects** — Exploits database with featured projects + freelance sites
6. **Certifications** — Access keys grid
7. **Contact** — Terminal-styled contact with direct links

## Customization

**Content:**
- Edit HTML inline to update name, bio, skills, experience
- Project links already point to your live sites (caterworld4u.com, ayahbahrain.com, etc.)

**Colors:**
- Search for `:root {` in the `<style>` block and modify variables

**Boot Sequence:**
- Scroll to the `bootLines` array in `<script>` and customize the system messages
- Adjust delays for boot speed

## Deployment

**Vercel** (recommended):
```bash
npx vercel deploy
```

**Netlify:**
- Drag the folder into Netlify dashboard
- Or `netlify deploy`

**GitHub Pages:**
- Push to repo, enable Pages from Settings

## Browser Compatibility

- Chrome/Edge ✅ (best experience)
- Firefox ✅
- Safari ✅
- Mobile browsers ✅

## Credits

Built by F.R.I.D.A.Y — inspired by Mr. Robot (USA Network).
Joel Karikkandathil © 2026 — Manama, Bahrain.
