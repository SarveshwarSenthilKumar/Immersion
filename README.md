# IMMERSION — The Single Story of a Developer

A techno-psychological drama and essay film exploring the myth of the lone genius, the ethics of innovation, and the ghosts of creation and ambition.

## Overview

**IMMERSION** is a non-linear cinematic odyssey through the single story of a developer filled with ups and downs of code. The film weaves together the intensity of *The Social Network*, the moral quandaries of *Frankenstein*, and the technological dilemmas of *Jurassic Park*.

- **Genre**: Techno-Psychological Drama / Essay Film
- **Directed by**: Sarveshwar Senthil Kumar
- **Premiere**: Fall 2026 — ONLINE
- **Languages**: English, with fragments of code & silence
- **Shot in**: Toronto & the digital sprawl

## Project Structure

```
Immersion/
├── index.html              # Main landing page with ticket 
├── FullScreenplay.txt      # Complete screenplay
├── Meaning.txt             # Scene breakdown & literary analysis
└── README.md               # This file
```

## Features

### Landing Page (`index.html`)

The main website features an immersive, cinematic design with:

- **Dark cinematic aesthetic** with grain overlay, scanlines, and floating particles
- **Interactive ticket portal** with QR code integration
- **Fake seat selection modal** showing sold-out screening (immersive experience)
- **Direct access** to screenplay and meaning documents
- **Navigation** to official site, trailer, and director's portfolio
- **Responsive design** for mobile and desktop

### Key Interactive Elements

- **RESERVE YOUR SEAT** button opens a seat selection modal with all seats marked as sold-out
- **FULL SCREENPLAY** button opens `FullScreenplay.txt` in a new tab
- **MEANING & BREAKDOWN** button opens `Meaning.txt` in a new tab
- **TRAILER** link opens the official trailer on Google Drive
- **DIRECTOR** link opens Sarveshwar Senthil Kumar's portfolio
- **QR Code** scans to the official Immersion website

## How to Use

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/sarveshwarsenthilkumar.github.io/Immersion.git
   cd Immersion
   ```

2. Open `index.html` in a web browser:
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

3. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

   Then navigate to `http://localhost:8000`

### Deployment

This is a static site that can be deployed to any static hosting service:

- **GitHub Pages**: Already configured at `sarveshwarsenthilkumar.github.io/Immersion`
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **Any web server**: Upload the files

## External Links

- **Official Website**: https://sarveshwarsenthilkumar.github.io/Immersion
- **Trailer**: https://drive.google.com/file/d/1wxzMYKnWVyp84z2UDtDpip4xsPvinRg9/view?usp=sharing
- **Director's Portfolio**: https://sarveshwarsenthilkumar.github.io/

## Documents

### FullScreenplay.txt

Contains the complete screenplay for IMMERSION. Open via the "FULL SCREENPLAY" button on the landing page or directly in your text editor.

### Meaning.txt

Contains scene-by-scene analysis, literary references, hidden layers, and the deeper meaning behind the film. Open via the "MEANING & BREAKDOWN" button or directly in your text editor.

## Technical Details

### Technologies Used

- **HTML5** for structure
- **CSS3** for styling (gradients, animations, glassmorphism)
- **Vanilla JavaScript** for interactivity
- **QRCode.js** (CDN) for QR code generation

### Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile-responsive design
- Requires JavaScript for full functionality

## Credits

- **Written & Directed by**: Sarveshwar Senthil Kumar
- **Official Selection**: Future of Cinema Forum

## License

© 2026 IMMERSION. All rights reserved.

## Contact

For press inquiries, collaboration opportunities, or questions about the film, please visit the official website or contact through the director's portfolio.

---

*"IMMERSION questions the myth of the lone genius. It's a horror story, a coming-of-code, and a love letter to the machines that shape us."*

*"Everything comes from something before." — Northrop Frye*
