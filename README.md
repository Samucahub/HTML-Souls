# ⚔️ HTML SOULS: Mini Edition ⚔️

*A tiny, browser-based souls-like adventure*

![HTML Souls Mini Edition](https://i.imgur.com/placeholder.jpg)

## What is this madness?

Ever wanted to play Dark Souls but thought "man, this is too big, too complex, and runs on actual hardware"? Well, fear not! I've crammed the essence of dying repeatedly into a single HTML file that runs in your browser.

This is **HTML SOULS: Mini Edition** - a humble attempt to recreate that sweet, sweet suffering in pure HTML, CSS, and JavaScript. It's janky, it's buggy, and I'm weirdly proud of it.

## Features (because every README needs bullet points)

- **3D Graphics** powered by Three.js (I have no idea how it works, but it does!)
- **A knight** that sometimes loads, sometimes doesn't (keeps you on your toes)
- **Skeleton enemies** that actually move and try to kill you
- **A campfire** that works as a checkpoint (and looks suspiciously like a 3D model I found online)
- **Combat system** with directional attacks (only hits what's in front of you - revolutionary, I know)
- **Rolling/dodging** with invincibility frames (because if it's not in HTML Souls, is it even a souls-like?)
- **Souls collection** (currency for... absolutely nothing yet, but it's the principle that counts!)
- **Pause menu** that looks vaguely like Dark Souls if you squint really hard
- **Continue/New Game** functionality with auto-save (it even remembers your souls sometimes!)

## The Tech Stack (fancy words for "stuff I used")

| Technology | Purpose | How Well I Understand It |
|------------|---------|--------------------------|
| **HTML5** | Structure | 100% (it's just tags, right?) |
| **CSS3** | Making things look pretty | 70% (flexbox is still magic) |
| **JavaScript** | Making things work | 85% (callbacks are scary) |
| **Three.js** | 3D magic | 30% (I copy-pasted until it worked) |
| **GLTF/OBJ Loaders** | Loading models | 20% (why won't the textures load? OH NOW THEY LOADED) |
| **Cinzel Font** | Dark Souls aesthetic | 100% (it's a font, I installed it) |

## How to Run (if you dare)

1. Clone this repository (or download the ZIP like a caveman)
```
git clone https://github.com/yourusername/html-souls.git
```

2. Make sure your folder structure looks like this (or everything breaks):
```
html-souls/
├── index.html
├── knight/
│   ├── armor.jpg
│   ├── gen.face.jpg
│   └── knight.obj
├── Enemys/
│   └── Skeleton.glb
└── CampFire/
    ├── Campfire.mtl
    └── Campfire.obj
```

3. Run a local server (because browsers hate loading local files)
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx live-server

# Or just use VS Code's "Live Server" extension (the lazy way)
```

4. Open your browser and navigate to `http://localhost:8000`

5. Press SPACE to begin your suffering

## How to Play

```
WASD          - Move (like every game since 1998)
Left Click    - Attack (only works if enemy is in front of you - realism!)
Right Click + Move - Rotate camera (bothered me for hours)
SHIFT         - Roll/dodge (3 second cooldown - no infinite rolling!)
SPACE         - Jump (you can jump in HTML Souls now, I guess)
L             - Lock-on to enemies (fancy!)
E             - Interact with bonfire (rest and respawn enemies)
ESC           - Pause (catch your breath, you'll need it)
```

## Known Issues (features, really)

- Models sometimes load, sometimes don't (keeps you on your toes)
- Textures are hit or miss (adds to the authentic HTML Souls mystery)
- Enemies might clip through each other (they're just really friendly)
- The sword might float slightly away from the hand (magic weapon enchantment)
- Performance on potato PCs may vary (upgrade your potato)

## Contributions

Okay, let's be real here: **I have absolutely no idea what I'm doing with Three.js or 3D modeling**.

This entire project was a learning experiment - me staring at documentation, crying into my keyboard, and celebrating when something rendered on screen. Every feature you see was built through:

- Hours of Googling error messages
- Stack Overflow copy-pasting with minor modifications
- Staring at Three.js examples until my eyes bled
- Trial and error (mostly error)
- That one friend who knows 3D math and took pity on me

**So yes, contributions are MORE than welcome!**

Whether you:
- Actually know how to position 3D models properly
- Understand quaternions (witches, all of you)
- Can fix the texture mapping
- Want to add proper animations
- Have better 3D models to replace my janky ones
- Just want to clean up my spaghetti code
- Have creative ideas for features

**PLEASE, I BEG YOU, HELP ME**

Open issues, submit pull requests, send carrier pigeons - anything helps! I genuinely want to learn and improve this project, and I'm not too proud to admit I need help.

## Special Thanks

- **The Three.js community** for existing and providing examples I could butcher
- **Stack Overflow** for being there at 3 AM when nothing worked
- **Coffee** for keeping me awake during debugging sessions
- **Dark Souls** for being the greatest game ever made and inspiring this mess
- **You** for actually reading this and maybe even playing the game

## License

Do whatever you want with this code. Sell it, burn it, frame it on your wall - I don't care. If you make millions, buy me a coffee? If you break something, it wasn't me.

---

*P.S. - If you actually play this and it works, please let me know. I haven't tested it on anything except my own machine and a prayer.*
