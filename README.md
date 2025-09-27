# My Technical Specification

This repository contains a technical specification created using [Spec-Up](https://github.com/decentralized-identity/spec-up), a tool for creating rich specification documents from markdown.

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/lukefryer1234/my-spec-repo.git
   cd my-spec-repo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Building the Specification

To build and view the specification:

- **Development mode** (watches for changes): `npm run edit`
- **Single build**: `npm run render`
- **Debug mode**: `npm run dev`

The rendered HTML will be output to the `build/` directory.

## Project Structure

- `spec.md` - The main specification document
- `specs.json` - Configuration file for Spec-Up
- `package.json` - Node.js project configuration
- `build/` - Generated HTML output (created after first build)

## Contributing

1. Make changes to `spec.md`
2. Run `npm run render` to generate the HTML
3. Open `build/index.html` in your browser to preview
4. Commit your changes and push to the repository

## License

[Add your license information here]