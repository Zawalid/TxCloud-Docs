# TXCloud Documentation

This is the Mintlify documentation for TXCloud API platform.

## Quick Start

### Prerequisites

- Node.js 18+
- npm, yarn, or pnpm

### Installation

```bash
# Install Mintlify CLI
npm install -g mintlify

# Navigate to docs folder
cd txcloud-docs

# Start local preview
mintlify dev
```

### Development

The local server will start at `http://localhost:3000`.

Changes to MDX files will hot-reload automatically.

### Deployment

1. Push to GitHub
2. Connect to Mintlify dashboard
3. Auto-deploys on every push

## Structure

```
txcloud-docs/
├── docs.json              # Main configuration
├── openapi/               # OpenAPI specifications (7 APIs)
├── introduction.mdx       # Home page
├── quickstart.mdx         # Getting started
├── authentication.mdx     # Auth guide
├── rate-limits.mdx        # Rate limiting
├── concepts/              # Core concepts
├── guides/                # Step-by-step guides
├── api-reference/         # API reference pages
├── sdks/                  # SDK documentation
├── resources/             # Error codes, changelog, etc.
├── snippets/              # Reusable content
├── logo/                  # Brand logos
└── images/                # Documentation images
```

## Configuration

Edit `docs.json` to customize:

- Navigation structure
- Branding (colors, logos)
- API settings
- Analytics

## OpenAPI Integration

OpenAPI specs are in `/openapi/`. Mintlify auto-generates API reference pages.

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [MDX Components](https://mintlify.com/docs/content/components)
- [OpenAPI Integration](https://mintlify.com/docs/api-playground/openapi)

## Support

- Email: support@txcloud.io
- Discord: https://discord.gg/txcloud
