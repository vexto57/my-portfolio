# Vexto Portfolio — Yusuph Sylvester Michael

Professional multi-page personal portfolio with smooth page transitions, responsive design and downloadable CV.

---

## Folder Structure (how to arrange in VS Code)

```
portfolio/
├── index.html          ← Home page
├── about.html          ← About Me / Who Am I
├── cv.html             ← Curriculum Vitae
├── skills.html         ← Technical Skills
├── contact.html        ← Contact / Let's Talk
│
├── css/
│   └── style.css       ← All styles (shared)
│
├── js/
│   ├── main.js         ← Navigation, transitions, mobile menu
│   └── cv-download.js  ← CV download feedback
│
└── images/
    ├── cover-photo.jpg              ← MAIN hero photo (right side of home – like the man in sample)
    ├── profile-photo.jpg            ← About Me side photo (right side)
    ├── cv-side-photo.jpg            ← CV page right-side profile photo
    ├── contact-side.jpg             ← Optional contact page visual
    ├── Yusuph_Sylvester_Michael_CV.pdf  ← Professional CV (already generated)
    │
    ├── icon-home.png                ← Optional custom icons for home menu cards
    ├── icon-about.png
    ├── icon-skills.png
    ├── icon-cv.png
    ├── icon-contact.png
    │
    ├── skill-graphics.png           ← Optional skill icons
    ├── skill-programming.png
    ├── skill-networking.png
    ├── skill-database.png
    ├── skill-ai.png
    │
    ├── icon-email.png               ← Optional contact icons
    ├── icon-whatsapp.png
    ├── icon-instagram.png
    │
    ├── hobby-scifi.png              ← Optional hobby icons
    ├── hobby-photo.png
    ├── hobby-drip.png
    ├── hobby-arts.png
    ├── hobby-music.png
    ├── hobby-neuro.png
    ├── hobby-kids.png
    ├── hobby-worship.png
    ├── hobby-gym.png
    └── hobby-nature.png
```

---

## Required Images You Must Upload

Place these files inside the `images/` folder:

| File Name                    | Used On          | Description                                      |
|-----------------------------|------------------|--------------------------------------------------|
| `cover-photo.jpg`           | Home (index)     | Main cover photo of you (right side, like sample)|
| `profile-photo.jpg`         | About Me         | Side portrait photo                              |
| `cv-side-photo.jpg`         | C.V page         | Circular / profile style photo                   |
| `contact-side.jpg`          | Contact (optional)| Decorative image for contact page               |

**Optional custom icons** (if you want to replace Font Awesome icons):
- Menu cards: `icon-home.png`, `icon-about.png`, `icon-skills.png`, `icon-cv.png`, `icon-contact.png`
- Skills: `skill-graphics.png`, `skill-programming.png`, etc.
- Contact: `icon-email.png`, `icon-whatsapp.png`, `icon-instagram.png`
- Hobbies: `hobby-*.png` as listed above

> Currently the site uses professional **Font Awesome** icons so it looks good immediately.  
> To use your own images, replace the `<i class="fas ...">` with `<img src="images/your-file.png" alt="">` inside the icon boxes.

---

## How to Run in VS Code

1. Open the `portfolio` folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey) if you don’t have it.
3. Right-click `index.html` → **Open with Live Server**.
4. The site opens in your browser with live reload.

Alternatively just open `index.html` directly in any browser (some features like smooth transitions still work).

---

## Features Included

- Fixed responsive navigation bar (hamburger on mobile)
- Smooth page-to-page transition animation
- Home page matching the sample layout (cards left + photo right)
- About Me with bio, location, profile photo + hobbies with icons
- Full C.V with Education + Practical Experience + **Download PDF button**
- Skills page with 5 professional skill cards
- Contact page with working Email / WhatsApp / Instagram links
- Fully responsive for PC, tablet and phone
- Consistent dark theme with orange accent (matching sample)

---

## Text Replacements (as requested)

| Original Sample     | Replaced With              |
|---------------------|----------------------------|
| Home Products       | Home Page                  |
| Wears / Shoes       | Who Am I / About Me        |
| Electronic Products | What I Do / Skills         |
| Stationery          | Curriculum Vitae           |
| Food                | Contacts / Let's Talk      |
| Client              | Neat                       |
| Review              | Attention                  |
| Widegrafix          | Vexto                      |
| Let Your Product Speak | Experience the Reality  |

---

## CV Download

The button on the C.V page downloads the professional PDF:
`images/Yusuph_Sylvester_Michael_CV.pdf`

It already contains your full name, age, education history and practical experience in clean professional formatting.

---

Enjoy your portfolio!  
**Vexto — Experience the Reality**
