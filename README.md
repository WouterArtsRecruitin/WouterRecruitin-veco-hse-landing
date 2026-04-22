# Veco HSE Engineer — Landing Page

Recruitment landingspage voor **HSE Engineer (Environment)** bij Veco Precision B.V. in Eerbeek.

## Live
- Preview: [set Netlify URL hier]
- Production: `werkenbij.recruitin.nl/veco` (pending)

## Over de rol
HBO/WO starter (0-4 jaar) met milieu-affiniteit. Focus op Environment (E) binnen het bestaande QHSE-team van 6. Mentoring door Wim Workum en Bastiaan de Wit (HSE Engineers H&S). Groeipad naar Senior in 5 jaar binnen de internationale IDEX-groep.

## Techstack
- Pure HTML + CSS + native `<video>` elements (geen build, geen framework)
- Fonts: Google Fonts (Fraunces + system)
- Video assets: Veo 3.1 (16x9 en 9x16)
- Image assets: Nano Banana (Gemini 2.5 Flash Image)

## Structuur
```
index.html           # Landingspage
images/              # 3 stills (cleanroom, productievloer, damherten)
videos/              # 4 Veo videos (cleanroom, tablet, walking, damherten)
netlify.toml         # Caching + security headers
```

## Deploy naar Netlify
1. New site from Git → selecteer deze repo
2. Build command: *(leeg laten)*
3. Publish directory: `/`
4. Deploy

Elke push naar `main` = auto-redeploy.

## Brand
- Primair: Veco magenta `#e06299`
- Secundair: Veco cyan `#4fc4cb`
- Donker: `#2f3541`

## Contact
**Wouter Arts** · Recruitin B.V. · warts@recruitin.nl · +31 6 14 31 45 93
