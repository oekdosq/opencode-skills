# OpenCode Skills Pack

18 skills untuk AI coding models (OpenCode, 0x Alpha, dll).

## Skills

| Skill | Fungsi |
|-------|--------|
| `ai-ui-patterns` | Design patterns untuk AI-powered React UI |
| `banner-design` | Desain banner (22 styles, social/ads/web/print) |
| `brand` | Brand identity, voice, visual identity |
| `design` | Comprehensive design (logo, CIP, mockups, slides, banners, icons) |
| `design-system` | Token architecture, component specs, slide generation |
| `deploy-to-vercel` | Deploy apps ke Vercel |
| `frontend-design` | Production-grade frontend interfaces |
| `gpt-tasteskill` | Elite UX/UI & GSAP Motion Engineer |
| `hallmark` | Anti-AI-slop design skill |
| `humanizer` | Remove AI writing patterns dari text |
| `imagegen-frontend-web` | Generate website design reference images |
| `react-render-optimization` | React rendering performance optimization |
| `slides` | Strategic HTML presentations dengan Chart.js |
| `ui-styling` | Beautiful UI dengan shadcn/ui + Tailwind |
| `ui-ux-pro-max` | Full UI/UX intelligence (79 styles, 192 palettes, 74 fonts) |
| `vercel-react-best-practices` | React/Next.js performance dari Vercel Engineering |
| `vercel-react-view-transitions` | Smooth native-feeling animations dengan View Transition API |
| `web-design-guidelines` | Review UI code untuk Web Interface Guidelines compliance |

## Cara Install

### OpenCode
Copy folder skill ke direktori project:
```
.opencode/skills/[nama-skill]/SKILL.md
```

### 0x Alpha / Model Lain
Copy folder skill ke direktori yang di-include dalam context model:
```
.agents/skills/[nama-skill]/SKILL.md
```

### Structure
Setiap skill minimal punya:
```
[skill-name]/
├── SKILL.md           ← instruksi utama (wajib)
├── references/        ← data referensi (opsional)
├── scripts/           ← helper scripts (opsional)
└── templates/         ← templates (opsional)
```

## Usage
Aktifkan skill dengan menyebut namanya di prompt, atau load manual:
```
Use the ui-ux-pro-max skill for this task.
```

## License
Personal use. Dari komunitas OpenCode.
