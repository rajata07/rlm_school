# RLM Public Sr. Sec. School Website

## Project Overview
School website for **RLM Public Sr. Sec. School**, Top Khanna, Kapurthala 144601, Punjab, India.
- **Established:** 1996
- **Director:** Shri K.K. Arora
- **Education:** Pre-Primary (Nursery, LKG, UKG) to Senior Secondary (Class XII)
- **Students:** ~500 | **Teachers:** ~30
- **Phone:** +91-9815230789
- **Email:** rlmschool@gmail.com
- **Facebook:** https://www.facebook.com/p/RLM-Public-SrSecSchool-100057081084611/
- **UPI Payment:** 9815230789@ptsbi (Paytm)

## Tech Stack
- Pure HTML/CSS/JS (no frameworks, no build tools)
- Google Fonts (Poppins), Font Awesome 6.5.1 icons
- Responsive design with CSS Grid, mobile hamburger menu

## Site Structure
| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero, about snippet, programs, why choose us, fee payment, contact form, map |
| About | `about.html` | History, director message, vision/mission, core values |
| Academics | `academics.html` | Detailed breakdown of each academic level |
| Facilities | `facilities.html` | 12 facility cards (currently hidden from nav) |
| Gallery | `gallery.html` | Photo gallery with lightbox, Facebook link |
| Contact | `contact.html` | Contact info cards, enquiry form, Google Maps |

## Navigation Order
Home → Academics → Gallery → About Us → Contact → [Pay Fees btn] → [Admissions Open btn]
- Facilities page exists but is hidden from navigation.

## Image Inventory (`images/` folder)

### Named/Purpose Images
| Filename | Dimensions | Content Description | Used In |
|----------|-----------|---------------------|---------|
| `school-building.jpg` | 1511×2015 (portrait) | School building exterior — heritage yellow architecture with green trees, iron fence, scooter in foreground. Shot from outside looking up. | Homepage about section, About page campus section, Gallery |
| `staff-group.jpg` | 1440×1080 (landscape) | Director K.K. Arora (center, blue striped shirt) standing with ~18 female teachers/staff in front of school's heritage arched entrance. | About page director section, Gallery |
| `paytm.jpeg` | — | Paytm UPI QR code for fee payment. UPI ID: 9815230789@ptsbi. Shows circular photo of K.K. Arora at top. | Homepage fee payment section |
| `gallery-1.jpg` | 1600×1200 (landscape) | Prize distribution ceremony — Director presenting gift to a small girl on stage, RLM banner behind, teachers watching. Winter event. | Gallery, Homepage |
| `gallery-2.jpg` | 1600×1200 (landscape) | Annual function — large crowd of kids in fancy dress/costumes sitting on ground, teachers seated behind, Director at center table. Winter. | Gallery, Academics (Sr. Secondary) |
| `gallery-3.jpg` | 1040×780 (landscape) | Kids performing dance on stage — RLM banner "Top Khanna, Kapurthala" behind, audience watching from ground. | Gallery, Academics (Middle School) |
| `gallery-4.jpg` | 1280×853 (landscape) | Pre-primary girls in white dresses holding red paper hearts, dancing in courtyard. RLM banner visible. Marigold petals on ground. | Gallery, Academics (Pre-Primary) |
| `gallery-5.jpg` | 720×960 (portrait) | Two primary-age girls in school uniform (blue polo + grey skirt) doing "Master Chef" activity — paper chef hats, decorated bread. Classroom setting. | Gallery, Academics (Primary) |
| `gallery-6.jpg` | 720×960 (portrait) | Boy in blue uniform with "Master Chef" paper hat, sitting at desk with bread basket. Classroom with other students behind. | Gallery |
| `gallery-7.jpg` | 960×640 (landscape) | Two girls dancing on stage in traditional Indian outfits (pink lehenga & golden dress). RLM banner behind. Cultural event. | Gallery, Academics (Secondary) |
| `gallery-8.jpg` | 960×640 (landscape) | Pre-primary girls in white dresses with red hearts, posing. RLM banner "Kapurthala" behind. Close-up group shot. | Gallery |
| `gallery-9.jpg` | 1040×488 (wide landscape) | "Farewell Party" title displayed on a Dell monitor screen — red and white design with "R.L.M Public Sr. Sec. School, Top Khanna, Kapurthala". | Gallery |
| `cultural-collage.jpg` | 1152×2048 (tall portrait) | Collage of 3 photos from cultural programs — kids dancing in pink/white dresses, hearts theme, RLM banner. Dark background frame. | Gallery |

### Original Facebook Filenames (kept as copies)
These are the original files from Facebook. The named versions above are copies of these:
- `485264947_...` → `gallery-1.jpg` (prize distribution)
- `485353738_...` → `gallery-2.jpg` (annual function)
- `485380194_...` → `cultural-collage.jpg` (dance collage)
- `485685290_...` → `gallery-3.jpg` (stage performance)
- `485786867_...` → `gallery-4.jpg` (pre-primary hearts dance)
- `69890087_...` → `gallery-5.jpg` (master chef girls)
- `69895704_...` → `school-building.jpg` (building exterior)
- `70044547_...` → `gallery-6.jpg` (master chef boy)
- `71500033_...` → `gallery-7.jpg` (two girls dancing)
- `71670520_...` → `gallery-8.jpg` (pre-primary hearts group)
- `87816838_...` → `gallery-9.jpg` (farewell screen)
- `main_image.jpg` → `staff-group.jpg` (staff with director)

## CSS Notes
- `school-building.jpg` is portrait (1511×2015) — uses `object-position: center top` to show building roof
- `staff-group.jpg` is landscape — director section uses `grid-template-columns: 1fr 1fr` (not fixed 300px)
- All gallery items use `object-fit: cover` with fixed 250px height
- Academic section images: 300px height, `object-fit: cover`

## Key Design Decisions
- No login system
- No backend — form submission shows alert only
- Fee payment via Paytm QR (active), other methods show "Coming Soon"
- Green "Pay Fees" button in navbar
- Scroll-reveal animations on cards
- Lightbox for gallery images
