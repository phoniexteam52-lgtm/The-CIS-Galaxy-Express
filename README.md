<div align="center">

<img src="docs/images/logo.png" alt="The CIS Galaxy Express logo" width="160">

# Twin Rover Quest

**Two robots. Built for 90 days. Never forgotten.**

A story-game website that tells children under 10 the true story of **Spirit** and **Opportunity**, the twin NASA rovers left on Mars.

[![Play the game](https://img.shields.io/badge/Play-Twin%20Rover%20Quest-FFC857?style=for-the-badge&labelColor=0B1B3A)](https://phoniexteam52-lgtm.github.io/The-CIS-Galaxy-Express/)
[![NASA Space Apps 2026](https://img.shields.io/badge/NASA%20Space%20Apps-2026-2EC4B6?style=for-the-badge&labelColor=0B1B3A)](https://www.spaceappschallenge.org)
[![Challenge](https://img.shields.io/badge/Challenge-Abandoned%20but%20not%20Forgotten-FF6B4A?style=for-the-badge&labelColor=0B1B3A)](https://www.spaceappschallenge.org)

**Team The CIS Galaxy Express · Cairo, Egypt**

<img src="docs/images/home.jpg" alt="Twin Rover Quest home screen" width="820">

</div>

---

## Contents

- [Summary](#summary)
- [The challenge](#the-challenge)
- [How it works](#how-it-works)
- [Screenshots](#screenshots)
- [The Mission Map and levels](#the-mission-map-and-levels)
- [Ask the Rover](#ask-the-rover)
- [The printed cartoon book](#the-printed-cartoon-book)
- [Designed for children](#designed-for-children)
- [What is built and what is concept](#what-is-built-and-what-is-concept)
- [Technology](#technology)
- [Run it locally](#run-it-locally)
- [Project structure](#project-structure)
- [NASA data and resources](#nasa-data-and-resources)
- [Other data, resources and tools](#other-data-resources-and-tools)
- [Use of AI](#use-of-ai)
- [Team](#team)
- [Project files](#project-files)
- [Credits and disclaimer](#credits-and-disclaimer)

---

## Summary

Twin Rover Quest is a story-game website that tells children under 10 the true story of Spirit and Opportunity, the twin NASA rovers left on Mars. Built for a 90-day mission, Spirit kept working for more than six years and Opportunity for more than fourteen. Both are still on Mars today, silent.

Children meet the twins and tap their parts to learn what each one did. Then they play through the rovers' journey on a Mission Map of five levels and a finale. Each level links **one engineering part to one real discovery**. Players earn badges, ask the rovers questions in a helper that answers only from NASA facts, and end by reading each robot's imagined letter.

Every fact links to its NASA source, and imagined voices are clearly labelled. **Level 1 is fully playable** in our prototype; Levels 2 to 5 are designed as concept screens.

| Planned mission | Spirit worked | Opportunity worked | Levels | Badges | Play time |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 90 days | 6+ years | 14+ years | 5 + finale | 6 | 15–20 min |

---

## The challenge

> **Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars**

We chose two machines NASA left on Mars: the twin rovers Spirit and Opportunity. They landed in January 2004 with a 90-day plan. Spirit kept working until March 2010 and Opportunity until June 2018. Most children have never heard of them.

**Our question:** how can a child under 10 feel why these robots matter, and still learn only true facts?

---

## How it works

In 15 to 20 minutes, a child:

1. **Meets the twins** and taps five rover parts to learn what each one does.
2. **Plays five short levels:** landing, digging, winter, the water clues and the dust storm.
3. **Collects one badge per level** and unlocks one page of a printed cartoon book.
4. **Asks the rovers questions** in the Ask the Rover helper.
5. **Reads each robot's letter** and sees where it is today.

<table>
<tr>
<td align="center" width="50%"><img src="docs/images/rover-spirit.png" alt="Cartoon of Spirit with a coral MER-A badge" width="220"><br><b>Spirit (MER-A)</b><br>Gusev Crater · worked until March 2010 · drove 7.73 km<br>Today: Troy, Gusev Crater, silent</td>
<td align="center" width="50%"><img src="docs/images/rover-opportunity.png" alt="Cartoon of Opportunity with a teal MER-B badge" width="220"><br><b>Opportunity, "Oppy" (MER-B)</b><br>Meridiani Planum · worked until June 2018 · drove 45.16 km<br>Today: Perseverance Valley, silent</td>
</tr>
</table>

The twins look the same in real life. In our cartoon only, Spirit wears a **coral** badge and Oppy a **teal** one, so children can tell them apart.

---

## Screenshots

| Meet the Twins | Mission Map |
| :---: | :---: |
| <img src="docs/images/meet-the-twins.jpg" alt="Meet the Twins screen with the arm card open" width="420"> | <img src="docs/images/mission-map.jpg" alt="Mission Map with badges and progress" width="420"> |
| Tap a part to see what it does and the discovery it led to | Six stops, badges and progress |

| Level 1: briefing | Level 1: landing |
| :---: | :---: |
| <img src="docs/images/level1-briefing.jpg" alt="Level 1 briefing from Mission Control" width="420"> | <img src="docs/images/level1-landing.jpg" alt="Level 1 landing with the parachute out" width="420"> |
| Mission Control sets the scene; the child picks who lands first | Tap PARACHUTE, AIRBAGS, ROCKETS and CUT at the right moment |

| Level 1: result | Letters from Mars |
| :---: | :---: |
| <img src="docs/images/level1-result.jpg" alt="Level 1 result with stars and badge" width="420"> | <img src="docs/images/letters-from-mars.jpg" alt="Oppy's imagined letter and the status cards" width="420"> |
| Stars, the Six-Minute Hero badge and the true bounce count | Each robot's imagined letter and where it is today |

<p align="center"><img src="docs/images/ask-the-rover.jpg" alt="Ask the Rover panel" width="640"><br><i>Ask the Rover: question chips, a Spirit/Oppy voice switch and a source on every answer</i></p>

---

## The Mission Map and levels

| Stop | Level | What the child does | Engineering part → discovery | Badge | Status |
| :---: | --- | --- | --- | --- | --- |
| 1 | **Crash Landing** | Taps PARACHUTE, AIRBAGS, ROCKETS and CUT, then counts the bounces | Airbag landing system → a working rover on the ground | Six-Minute Hero | ✅ Playable |
| 2 | **The Wheel That Wouldn't Quit** | Drives Spirit backwards with a stuck wheel and tests the bright soil | Wheels → nearly pure silica, a sign of ancient hot water | Silica Finder | Concept |
| 3 | **Winter on Low Ridge** | Parks Spirit on a sunny slope and spends a small power budget | Solar panels → the 360° McMurdo panorama | Sun Chaser | Concept |
| 4 | **Blueberries and the Salty Sea** | Matches three robot tools to three clues | Arm instruments → a shallow, salty sea once covered Meridiani | Water Detective | Concept |
| 5 | **The Dust Storm** | Takes panorama frames as the Sun dims | Solar panels and batteries → Oppy's last 360° view | Last Panorama | Concept |
| ★ | **Letters from Mars** | Reads each robot's imagined letter | — | Never Forgotten | ✅ Working |

**Kind by design:** no game-over screen. A miss shows "Try again" with a hint, and after two misses Auto-pilot finishes the step. Level 1 also has *Slow motion*, *Tap anywhere* and keyboard play (Space or Enter).

---

## Ask the Rover

A helper that answers a child's question in Spirit's or Oppy's voice, **only from facts the team checked on NASA pages**. Anything else gets "I don't know."

| Child asks | Rover answers |
| --- | --- |
| Did you find life? | No. I found clues about a place where life could live. NASA does not say life was there. |
| Where are you now? | I finished my mission and went quiet. I am still on Mars, but I cannot talk to Earth anymore. |
| What are blueberries? | Tiny gray balls, about as big as BBs. They are rocks full of iron. Please do not eat them! |

Rules: a source chip on every fact; never calls the rovers "alive", "dead" or "junk"; never asks for or keeps a child's name or data. The prototype uses **prepared answers, not an AI model**. A version with an AI model limited to the same fact sheet is planned.

---

## The printed cartoon book

A 12-page A5 cartoon booklet (three A4 sheets, folded and stapled). Each page has cartoon panels, a "NASA fact" box, a real NASA photo with its credit, and a QR code that says **"Play this level"**. The codes are plain and static, with no tracking or sign-in. *Status: concept.*

---

## Designed for children

**How we write**
- One idea per card, sentences of about 12 words or fewer.
- Robot speech bubbles are labelled "Spirit says" or "Oppy says": the imagined voice.
- Every real fact sits in a **NASA fact** box with its source.
- We say "went quiet" and "still on Mars today", never "dead", "trash" or "junk".

**Accessibility and privacy**
- Buttons are at least 56 px tall; nothing to tap is smaller than 44 px.
- Sound is off by default, and every sound has a caption or animation.
- Motion stops when the device asks for reduced motion.
- Progress stays in the browser: no names, no accounts, nothing sent anywhere.

**Palette**

| Swatch | Role | Hex |
| :---: | --- | --- |
| ![](https://img.shields.io/badge/-%20%20%20%20-C1440E?style=flat-square) | Mars ground (rust) | `#C1440E` |
| ![](https://img.shields.io/badge/-%20%20%20%20-F2D2A9?style=flat-square) | Mars sand, panels | `#F2D2A9` |
| ![](https://img.shields.io/badge/-%20%20%20%20-0B1B3A?style=flat-square) | Space background (night navy) | `#0B1B3A` |
| ![](https://img.shields.io/badge/-%20%20%20%20-FFF8EC?style=flat-square) | Cards (cream) | `#FFF8EC` |
| ![](https://img.shields.io/badge/-%20%20%20%20-FF6B4A?style=flat-square) | Spirit badge (coral) | `#FF6B4A` |
| ![](https://img.shields.io/badge/-%20%20%20%20-2EC4B6?style=flat-square) | Opportunity badge (teal) | `#2EC4B6` |
| ![](https://img.shields.io/badge/-%20%20%20%20-FFC857?style=flat-square) | Stars, rewards, buttons | `#FFC857` |
| ![](https://img.shields.io/badge/-%20%20%20%20-1B1B2F?style=flat-square) | Text (ink) | `#1B1B2F` |

---

## What is built and what is concept

| Component | Status |
| --- | --- |
| Home, Meet the Twins and Mission Map | ✅ Working prototype |
| Level 1: Crash Landing | ✅ Playable |
| Letters from Mars and status cards | ✅ Working prototype |
| Ask the Rover with prepared answers | ✅ Working prototype |
| Levels 2 to 5 | 🟡 Concept screens |
| Printed cartoon book with QR codes | 🟡 Concept |
| Ask the Rover with a limited AI model | ⏳ Planned |
| Read-aloud, large text, Arabic mode | ⏳ Planned |

---

## Technology

| Area | What we used |
| --- | --- |
| Languages | HTML, CSS, JavaScript, in one self-contained page with no build step |
| Art | SVG cartoon rovers and landing scenes, drawn in code |
| Icons | Inline SVG line icons based on [Lucide](https://lucide.dev) (ISC) and [Feather](https://feathericons.com) (MIT) |
| Fonts | [Fredoka](https://fonts.google.com/specimen/Fredoka) and [Nunito](https://fonts.google.com/specimen/Nunito) (SIL Open Font License 1.1) |
| Sound | Short tones from the browser's [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API), off by default |
| Progress | Browser `localStorage`, no accounts |
| Hosting | [GitHub Pages](https://pages.github.com) |

---

## Run it locally

No install is needed.

```bash
git clone https://github.com/phoniexteam52-lgtm/The-CIS-Galaxy-Express.git
cd The-CIS-Galaxy-Express
# open index.html in any modern browser
```

Or play it online: **https://phoniexteam52-lgtm.github.io/The-CIS-Galaxy-Express/**

---

## Project structure

```
The-CIS-Galaxy-Express/
├── index.html                                 # the whole website (HTML, CSS, JS, SVG art)
├── README.md
└── docs/
    ├── Twin_Rover_Quest_Documentation.docx    # full project documentation
    ├── Twin_Rover_Quest_Presentation.pptx     # 7-slide presentation with speaker notes
    └── images/                                # logo, rover art and screenshots used in this README
```

---

## NASA data and resources

The project is built on NASA's **Mars Exploration Rover (MER)** mission: Spirit (MER-A, 2004–2010) and Opportunity (MER-B, 2004–2018). We used NASA mission pages, technical papers and Photojournal images as the source of our facts, numbers, dates and pictures. The team rewrote each fact in simple English for children.

| # | Resource | Used for |
| :---: | --- | --- |
| 1 | [NASA Science: Spirit (MER-A) mission page](https://science.nasa.gov/mission/mer-spirit) | Spirit's status card and dates |
| 2 | [NASA JPL: NASA Concludes Attempts to Contact Mars Rover Spirit](https://www.jpl.nasa.gov/news/nasa-concludes-attempts-to-contact-mars-rover-spirit/) | Spirit's last message (Mar 22, 2010) and end of contact (May 25, 2011) |
| 3 | [NASA JPL: NASA's Opportunity Rover Mission on Mars Comes to End](https://www.jpl.nasa.gov/news/nasas-opportunity-rover-mission-on-mars-comes-to-end/) | Opportunity's last message, 835+ commands, 45.16 km, 60× its plan |
| 4 | [NASA Technical Reports Server: MER Entry, Descent and Landing](https://ntrs.nasa.gov/api/citations/20040085793/downloads/20040085793.pdf) | Level 1 landing order and about 343 seconds of landing |
| 5 | [NASA TFAWS 2005: MER landing thermal paper](https://tfaws.nasa.gov/TFAWS05/Website/files/ThermalPaperSession/TFAWS05_GTsuyuki_TH.pdf) | Level 1: the landing ran automatically |
| 6 | [NASA Photojournal: Opportunity Bounces to a Stop](https://science.nasa.gov/photojournal/opportunity-bounces-to-a-stop/) | Level 1 bounce path |
| 7 | [NASA: Opportunity Rover Launches to Mars, July 7, 2003](https://www.nasa.gov/image-article/july-7-2003-nasas-opportunity-rover-launches-mars/) | Launch dates in the Level 1 briefing |
| 8 | [NASA Kennedy Space Center: 2003 photo gallery](https://science.ksc.nasa.gov/gallery/photos/2003/) | Spirit launch photos |
| 9 | [NASA JPL: Three Generations of NASA Mars Rovers (PIA11436)](https://www.jpl.nasa.gov/images/pia11436-newest-is-biggest-three-generations-of-nasa-mars-rovers/) | Rover size on the Meet the Twins cards |
| 10 | [NASA Photojournal: First Grinding of a Rock on Mars](https://science.nasa.gov/photojournal/first-grinding-of-a-rock-on-mars/) | The arm's rock grinder (Adirondack, Feb 6, 2004) |
| 11 | [NASA Photojournal: Rover's Wheel Churns Up Bright Martian Soil (PIA11757)](https://science.nasa.gov/photojournal/rovers-wheel-churns-up-bright-martian-soil) | Level 2: silica found on May 21, 2007 |
| 12 | [NASA Photojournal: Rover's Wheel Churns Up Bright Martian Soil, vertical (PIA11758)](https://science.nasa.gov/photojournal/rovers-wheel-churns-up-bright-martian-soil-vertical/) | Level 2 trench picture |
| 13 | [NASA Photojournal: Bright Soil Churned by Spirit's Sol 1861 Drive (PIA11967)](https://science.nasa.gov/photojournal/bright-soil-churned-by-spirits-sol-1861-drive/) | Level 2: driving backwards |
| 14 | [NASA Photojournal: Spirit in McMurdo Panorama (PIA16440)](https://science.nasa.gov/photojournal/spirit-mars-rover-in-mcmurdo-panorama/) · [image file](https://assets.science.nasa.gov/content/dam/science/psd/photojournal/pia/pia16/pia16440/PIA16440.jpg) | Level 3: winter on Low Ridge, April–October 2006 |
| 15 | [NASA Photojournal: Martian Concretions Near Fram Crater (PIA19113)](https://science.nasa.gov/photojournal/martian-concretions-near-fram-crater) | Level 4: the blueberries |
| 16 | [NASA Photojournal: "Berries" Here, There, Everywhere (PIA05588)](https://science.nasa.gov/photojournal/berries-here-there-everywhere) | Level 4 |
| 17 | [NASA APOD: A Berry Bowl of Martian Spherules (Apr 5, 2004)](https://science.nasa.gov/image-article/apod-2004-april-5-a-berry-bowl-of-martian-spherules/) | Level 4 close-up |
| 18 | [NASA Photojournal: Big Spherules near Victoria](https://science.nasa.gov/photojournal/big-spherules-near-victoria) | Level 4 |
| 19 | [NASA Photojournal: Opportunity Legacy Pan, true color](https://science.nasa.gov/photojournal/opportunity-legacy-pan-true-color) · [JPL (PIA22909)](https://www.jpl.nasa.gov/images/pia22909-opportunity-legacy-pan-true-color/) | Level 5: the last panorama, 354 frames, May 13–June 10, 2018 |

NASA photos are linked to their original pages and credited to NASA/JPL-Caltech and partners.

---

## Other data, resources and tools

We did not use data from any Space Agency Partner. The news reports below were used for facts only, rewritten in our own words; no text or images were copied.

| Resource | Used for |
| --- | --- |
| [Spaceflight Now: Spirit rover launch report (June 2003)](https://spaceflightnow.com/mars/mera/030604mer.html) | Rover size and weight |
| [Spaceflight Now: Girl names the Mars rovers (June 2003)](https://spaceflightnow.com/mars/mera/030608naming.html) | The naming story (Sofi Collis, age 9) |
| [Spaceflight Now: NASA briefing on a salty sea at Meridiani (Mar 23, 2004)](https://spaceflightnow.com/mars/mera/040323marswater.html) | Level 4 conclusion |
| [Mars Daily: Mineral in Mars Berries Adds to Water Story](https://www.marsdaily.com/reports/Mineral_In_Mars_Berries_Adds_To_Water_Story.html) | Level 4: hematite |
| [SpaceNews: report of the Mar 2, 2004 NASA briefing](https://spacenews.com/?p=40434) | Level 4: signs of liquid water |
| [VOA via GlobalSecurity: Opportunity mission ends (Feb 2019)](https://www.globalsecurity.org/space/library/news/2019/space-190213-voa01.htm) | Cross-check of Opportunity's numbers |
| [Solar Views: a sol is a Mars day (copy of NASA release, Feb 6, 2004)](https://solarviews.com/eng/spiritrover10.htm) | "Words to know" in the planned book |
| [UNT Web Archive: JPL MER missions page (2003)](https://webarchive.library.unt.edu/eot2008/20080917060130/http://mars.jpl.nasa.gov/missions/present/2003.html) | Mission background |
| [NASA Facts: Mars Exploration Rover (copy)](https://corpora.tika.apache.org/base/docs/govdocs1/998/998915.pdf) | Airbags and bounce counts |
| [Lucide Icons](https://lucide.dev) (ISC) and [Feather Icons](https://feathericons.com) (MIT) | Website and presentation icons |
| [Google Fonts: Fredoka](https://fonts.google.com/specimen/Fredoka) and [Nunito](https://fonts.google.com/specimen/Nunito) (SIL OFL 1.1) | Website fonts |
| [GitHub Pages](https://pages.github.com) | Hosting |
| [Claude by Anthropic](https://www.anthropic.com/claude) | AI assistant (see below) |

---

## Use of AI

**Yes, we used AI tools.** The challenge solution idea, story, level design, game script and choice of facts were created by our team. Every fact was checked by the team against NASA sources. The website itself runs no AI: Ask the Rover uses prepared answers.

| AI tool | What it did | Parts affected |
| --- | --- | --- |
| [Claude (Anthropic)](https://www.anthropic.com/claude), large language model | Improved the website design and usability; added the Lucide/Feather-based icons and our palette; rebuilt Level 1 from our script; redrew the cartoon rover illustration in SVG code; drafted the documentation, presentation and submission text | `index.html`, the rover illustrations, `docs/Twin_Rover_Quest_Documentation.docx`, `docs/Twin_Rover_Quest_Presentation.pptx`, this README |
| [to add] | Any other AI tool used (for example for the logo) | [to add] |

No AI-generated audio or voices were used. No AI-generated content uses or changes NASA logos, flags or mission insignia.

---

## Team

**The CIS Galaxy Express** · Creatives International Schools · Cairo, Egypt

| Member | Role |
| --- | --- |
| Islam Saeed Mohamed | Team leader |
| Farida Khaled Mamdouh | Member |
| Fady Ehab Abdelaziz | Member |
| Hamza Mohamed Salama | Member |
| Tawba Mohamed Ahmed | Member |

---

## Project files

- 🌐 **Website:** https://phoniexteam52-lgtm.github.io/The-CIS-Galaxy-Express/
- 📄 **Documentation:** [docs/Twin_Rover_Quest_Documentation.docx](docs/Twin_Rover_Quest_Documentation.docx)
- 📊 **Presentation (7 slides):** [docs/Twin_Rover_Quest_Presentation.pptx](docs/Twin_Rover_Quest_Presentation.pptx)

---

## Credits and disclaimer

Pictures from NASA are credited to NASA/JPL-Caltech, Cornell University, Arizona State University and USGS, as listed on each NASA page. The story, game design, robot voices and letters were made by our team; the robot voices and letters are imagined and labelled as such. Icons are based on Lucide and Feather. The cartoon rover illustration was redrawn in code with help from Claude (Anthropic).

A student project for the **NASA Space Apps Challenge 2026**. NASA has not reviewed or endorsed this project.

<p align="center"><i>Spirit and Oppy were left on Mars. Every kid who plays, reads and asks brings them back to life.</i></p>
