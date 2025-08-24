# Static Site Generator

A custom static site generator built from scratch that transforms raw content files (Markdown and images) into a complete static website with HTML and CSS.

## What Is This?

This static site generator takes your content files and converts them into a lightning-fast, secure, and easily hostable static website. Static sites are incredibly popular for blogs, portfolios, landing pages, and documentation because they offer excellent performance without the complexity of dynamic backends.

## Static vs. Dynamic Sites

### Static Sites (What This Generates)
Static sites have **fixed content** that doesn't change based on user interaction. They're perfect when you don't need:
- File uploads
- User authentication/login
- Comment systems
- User preference saving

### Ideal Use Cases
- **Blogs** - Content-focused websites
- **Portfolios** - Showcasing your work
- **Landing pages** - Marketing and promotional sites  
- **Documentation** - Technical guides and references

## Features

- 🚀 **Lightning Fast** - Pure HTML/CSS output for maximum performance
- 🔒 **Secure** - No server-side processing means fewer attack vectors
- 📝 **Markdown Support** - Write content in simple Markdown format
- 🖼️ **Image Processing** - Handles images and static assets
- 🌐 **Easy Deployment** - Deploy anywhere that serves static files

## Prerequisites

- Node.js (v14 or higher)
- Git

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/site-generator.git
cd site-generator

# Install dependencies
npm install
```

## Usage

```bash
# Generate your static site
npm run generate

# Serve locally for development
npm run serve

# Build for production
npm run build
```

## Project Structure

```
site-generator/
├── src/
│   ├── content/          # Your Markdown files
│   ├── assets/           # Images and static files
│   ├── templates/        # HTML templates
│   └── styles/           # CSS files
├── dist/                 # Generated static site
├── tests/                # Test files
└── README.md
```

## Content Creation

1. Add your Markdown files to `src/content/`
2. Place images and assets in `src/assets/`
3. Run the generator to create your static site
4. Find the generated HTML in the `dist/` folder

## Testing

```bash
# Run tests
npm test

# Run tests with coverage
npm run test:coverage
```

## Deployment

The generated static site in the `dist/` folder can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any web server that serves static files

## Development

This generator transforms:
- **Input**: Markdown files + assets
- **Output**: Complete HTML/CSS website

### How It Works

1. Reads Markdown files from the content directory
2. Parses frontmatter for metadata
3. Converts Markdown to HTML
4. Applies templates and styling
5. Copies assets to the output directory
6. Generates a complete static website

## Contributing

Improvements and suggestions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests for new features
5. Submit a pull request

## License

MIT License - see LICENSE file for details

## Acknowledgments

Inspired by popular static site generators like Hugo, Jekyll, and Gatsby.
