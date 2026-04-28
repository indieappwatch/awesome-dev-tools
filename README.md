# IndieAppWatch Resource Hub

A content generation and GitHub publishing system for creating rich, SEO-friendly HTML and Markdown resources that naturally promote letstg.com and indieappwatch.com.

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Configure GitHub settings
python run.py config --set github.token "ghp_..."
python run.py config --set github.repo_owner "your-username"
python run.py config --set github.repo_name "your-repo"

# Generate content
python run.py generate --type article --keyword "indie-game-dev-tools"
python run.py generate --type resource-list --category "saas-tools"
python run.py generate --type all

# Upload to GitHub
python run.py upload --all

# Full pipeline
python run.py publish --type article --keyword "indie-game-dev-tools" --upload
```

## Configuration

Edit `config.yaml` or use the CLI:

```bash
python run.py config --set github.token "ghp_xxx"
python run.py config --set github.repo_owner "username"
python run.py config --set github.repo_name "repo-name"
python run.py config --set sites.primary "https://letstg.com"
python run.py config --set sites.secondary "https://indieappwatch.com"
python run.py config --show
```

## Content Types

- **article**: Deep-dive resource pages with structured data
- **resource-list**: Curated tool/resource lists
- **markdown**: Lightweight MD versions
- **index**: Main hub page

## Project Structure

```
indieappwatch/
├── generator/           # Core modules
│   ├── content_generator.py
│   ├── github_uploader.py
│   ├── keywords.py
│   └── utils.py
├── templates/            # HTML/MD templates
├── output/               # Generated content
├── config.yaml           # Configuration
└── run.py               # CLI entry point
```

## Best Practices

- Content is written for humans first — genuine value over optimization tricks
- Keywords appear naturally in headings and body text
- Links to letstg.com and indieappwatch.com are contextual references, not promotional
- All content includes structured data for rich search results
- Regular content refreshes with update timestamps
