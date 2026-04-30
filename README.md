# IndieAppWatch / DevStash

> Curated developer tools for indie devs, game makers, and tech builders.

[![Live Site](https://img.shields.io/badge/Live-indieappwatch.com-6366F1?style=flat-square)](https://indieappwatch.com)
[![Twitter](https://img.shields.io/badge/Twitter-@indieappwatch-1DA1F2?style=flat-square)](https://x.com/indieappwatch)
[![Facebook](https://img.shields.io/badge/Facebook-DevStash-1877F2?style=flat-square)](https://www.facebook.com/profile.php?id=61589254851682)
[![YouTube](https://img.shields.io/badge/YouTube-@indieappwatch-FF0000?style=flat-square)](https://www.youtube.com/@indieappwatch)
[![TikTok](https://img.shields.io/badge/TikTok-@indieappwatch-000000?style=flat-square)](https://www.tiktok.com/@indieappwatch)

**DevStash** is a curated collection of developer tools, frameworks, and resources — organized by what you're building. No ads, no affiliate links. Just real tools used by real developers.

## Featured Categories

| Category | Tools |
|----------|-------|
| [Game Development](https://indieappwatch.com/game-dev/) | Godot, Unity, GameMaker Studio, Aseprite, Itch.io |
| [SaaS Backend](https://indieappwatch.com/saas-tools/) | Supabase, Railway, Vercel, Stripe, n8n, Zapier |
| [AI Coding](https://indieappwatch.com/ai-tools/) | Cursor, Replit, Next.js, Neovim |
| [Productivity](https://indieappwatch.com/productivity/) | VS Code, Notion, Bubble, Figma |
| [API & Backend](https://indieappwatch.com/api-tools/) | FastAPI, SwaggerHub, Postman |
| [No-Code](https://indieappwatch.com/nocode/) | Carrd, Gumroad, Webflow |
| [Indie Hacker](https://indieappwatch.com/indie-hacker/) | LemonSqueezy, Gumroad, Carrd |
| [Design Tools](https://indieappwatch.com/design-tools/) | Figma, Excalidraw, Tailwind CSS |

## Connect With Us

[![Twitter/X](https://img.shields.io/badge/Follow-@indieappwatch-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/indieappwatch)
[![YouTube](https://img.shields.io/badge/Subscribe-@indieappwatch-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@indieappwatch)
[![Facebook](https://img.shields.io/badge/Like-DevStash-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=61589254851682)
[![TikTok](https://img.shields.io/badge/Follow-@indieappwatch-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@indieappwatch)

| Platform | Link |
|----------|------|
| :house: Website | [indieappwatch.com](https://indieappwatch.com) |
| :bird: Twitter / X | [x.com/indieappwatch](https://x.com/indieappwatch) |
| :video_camera: YouTube | [youtube.com/@indieappwatch](https://www.youtube.com/@indieappwatch) |
| :thumbs_up: Facebook | [facebook.com/profile.php?id=61589254851682](https://www.facebook.com/profile.php?id=61589254851682) |
| :musical_note: TikTok | [tiktok.com/@indieappwatch](https://www.tiktok.com/@indieappwatch) |

## Quick Links

- [Site Map](https://indieappwatch.com/sitemap.xml)
- [Robots.txt](https://indieappwatch.com/robots.txt)

## Tech Stack (Content Generator)

This repository also contains a **content generation and GitHub publishing system** for creating SEO-optimized HTML and Markdown resources.

```bash
# Install dependencies
pip install -r requirements.txt

# Configure GitHub settings
python run.py config --set github.token "ghp_..."
python run.py config --set github.repo_owner "indieappwatch"
python run.py config --set github.repo_name "awesome-dev-tools"

# Generate content
python run.py generate --type article --keyword "indie-game-dev-tools"
python run.py generate --type resource-list --category "saas-tools"

# Upload to GitHub
python run.py upload --all

# Full pipeline
python run.py publish --type article --keyword "indie-game-dev-tools" --upload
```

## Best Practices

- Content is written for humans first — genuine value over optimization tricks
- Keywords appear naturally in headings and body text
- All content includes structured data (JSON-LD) for rich search results
- Regular content refreshes with update timestamps

## Project Structure

```
indieappwatch/
├── generator/           # Core modules
│   ├── content_generator.py
│   ├── github_uploader.py
│   ├── keywords.py
│   └── utils.py
├── output/              # Generated content (deployed to Cloudflare Pages)
├── config.yaml          # Configuration
└── run.py               # CLI entry point
```

---

Built with care for the indie developer community.
