# Site Generator

This site generator takes your content files and converts them into an easily hostable static website.

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
./main.sh
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
./test.sh
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

## Acknowledgments

Inspired by popular static site generators like Hugo, Jekyll, and Gatsby.
