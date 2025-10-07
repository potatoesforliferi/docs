# Gudtrip Documentation

Official documentation for Gudtrip - the world's first crypto-enabled cannabis vape device.

## About Gudtrip

Gudtrip is an innovative cannabis vape that rewards users with cryptocurrency for switching to healthier consumption methods. Powered by blockchain technology and built by the Puffpaw Foundation, Gudtrip combines premium cannabis vaporization with smart tracking and crypto incentives.

## Documentation Structure

This repository contains the complete Gudtrip documentation, including:

- **Getting Started**: Introduction and quickstart guides
- **Product Information**: Device features and market overview
- **Rewards System**: Gudtrip Points and invite campaign details
- **Developer Resources**: Technical documentation and APIs
- **AI Tools**: Guides for documentation contributors

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```bash
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```bash
cd docs
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes are deployed to production automatically after pushing to the master branch through the Mintlify GitHub app integration.

## Project Structure

```
docs/
├── index.mdx                 # Homepage
├── quickstart.mdx           # Getting started guide
├── device-features.mdx      # Product features
├── market-overview.mdx      # Market analysis
├── gudtrip-points.mdx       # Points system
├── invite-campaign.mdx      # Referral program
├── development.mdx          # Developer setup
├── docs.json               # Navigation & config
├── essentials/             # Documentation tools
├── ai-tools/               # AI setup guides
└── api-reference/          # API documentation
```

## Contributing

We welcome contributions to improve our documentation. Please ensure:

- All MDX files include proper YAML frontmatter
- Follow the established Mintlify component patterns
- Test changes locally before submitting
- Use clear, concise language appropriate for our audience

## Need Help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
- [Gudtrip support](mailto:support@gudtrip.com)

## License

Copyright © 2025 Puffpaw Foundation. All rights reserved.
