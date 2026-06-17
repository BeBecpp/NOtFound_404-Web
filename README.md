# NOtFound_404 Web

**Build · Secure · Ship**

NOtFound_404 is a Mongolia-based builder team focused on practical AI systems, full-stack product development, defensive cybersecurity, CTF practice, and polished user experiences.

This repository contains the official team website. The site is built as a clean, fast, single-page static website that presents the team identity, skill matrix, selected projects, member profiles, and contact links.

## Live Site

https://notfound404.asuu.app/

## Team Focus

NOtFound_404 is not only a CTF team. The team works across multiple engineering lanes:

- AI engineering and practical AI workflows
- Full-stack web development
- Frontend UI / UX and product interfaces
- Defensive cybersecurity and safe analysis
- Legal CTF practice and technical writeups
- Project presentation, demos, and public proof

## Brand Direction

The current team line is:

> **Build · Secure · Ship**

Meaning:

- **Build** — turn ideas into working systems
- **Secure** — think carefully about risk, validation, and defensive practice
- **Ship** — make projects usable, presentable, and easy to evaluate

## Website Sections

The website includes:

- **Home** — team positioning and high-level technical direction
- **Identity** — team principles and branding language
- **Work** — what the team builds and how the skill areas connect
- **Skills** — professional capability matrix
- **Projects** — selected builds with category filters
- **Team** — core member profiles and portfolio links
- **Process** — how the team turns ideas into proof
- **Contact** — public links and team email

## Core Team

### Bayarbayasgalan Enkhtulga  
**Team Lead · AI Engineer · Full-stack Developer**

Portfolio: https://bebecpp.github.io/my_blog/  
GitHub: https://github.com/BeBecpp

### Khuslen  
**Full-stack Developer · Cybersecurity Builder**

Portfolio: https://fluxknight.github.io/portfolio/  
GitHub: https://github.com/FluxKnight

### Tsogterdene Margaderdene  
**Cybersecurity Specialist**

Focused on cybersecurity fundamentals, CTF practice, Linux workflow, safe testing habits, and team-focused technical review.

## Featured Project Areas

The project grid highlights work across:

- AI products
- Full-stack prototypes
- Defensive security tools
- CTF utilities
- Data and computer vision experiments
- Frontend interaction projects
- Accessibility and team concepts

Example project directions include:

- BreachPilot
- TUTall
- HelioGuard AI
- SkillProof AI
- HuruInk
- TaliinAtlas
- MoodMeal AI
- Crypto Tool
- DevGuard AI
- AegisLink
- Runner Void
- Aura Guide

## Tech Stack

This website is intentionally simple and easy to deploy.

- HTML
- CSS
- JavaScript
- Static single-page structure
- Responsive layout
- No build step required

## Project Structure

```txt
NOtFound_404-Web/
├── index.html
└── README.md
```

All website code is currently contained inside `index.html`.

## Customization

### Change the team name

Inside `index.html`, update:

```js
const BRAND_NAME = 'NOtFound_404';
```

### Change team email

Search for:

```txt
pynotix.py@gmail.com
```

Replace it with the new team email.

### Edit projects

Inside `index.html`, update the `projects` array:

```js
const projects = [
  {
    name: 'Project Name',
    type: 'AI',
    category: 'ai fullstack',
    desc: 'Short project description.',
    tags: ['Python', 'AI', 'Demo'],
    url: 'https://example.com'
  }
];
```

Project filters are based on the `category` field.

Available category keywords:

- `ai`
- `fullstack`
- `security`
- `frontend`
- `data`
- `game`
- `team`

## Deployment

Because the site is static, it can be deployed on GitHub Pages, Vercel, Netlify, or any basic static hosting service.

### Basic Git workflow

```bash
git add index.html README.md
git commit -m "Update team website"
git push
```

## Development Notes

The site is designed to stay:

- fast
- responsive
- easy to rename
- easy to edit
- professional for portfolios, hackathons, and team introductions

No external framework is required.

## Contact

Team email:

**pynotix.py@gmail.com**

Public links:

- Team repository: https://github.com/BeBecpp/NOtFound_404-Web
- BeBe portfolio: https://bebecpp.github.io/my_blog/
- BeBe GitHub: https://github.com/BeBecpp
- FluxKnight portfolio: https://fluxknight.github.io/portfolio/
- FluxKnight GitHub: https://github.com/FluxKnight

## License

This project is currently maintained by the NOtFound_404 team. Add a license file if the repository becomes open for reuse or contribution.
