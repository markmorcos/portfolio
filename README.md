# Mark Morcos - Portfolio

My personal portfolio website built with Astro, showcasing my projects and professional experience. Visit [morcos.tech](https://morcos.tech) to see it live.

## 🚀 Tech Stack

- **Framework**: [Astro](https://astro.build) - For fast, content-focused static site generation
- **Styling**: [Tailwind CSS](https://tailwindcss.com) - For utility-first styling
- **Markdown**: MDX support for content management
- **Performance**:
  - Static site generation
  - Optimized images
  - Minimal JavaScript
- **SEO**: Built-in meta tags and structured data
- **Deployment**: Docker container with Nginx

## 🛠️ Development

### Prerequisites

- Node.js (v18 or later)
- npm or yarn
- Docker (for containerized deployment)

### Local Setup

1. Clone the repository:

```bash
git clone https://github.com/markmorcos/portfolio.git
cd portfolio
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

The site will be available at `http://localhost:4321`

### Build

To create a production build:

```bash
npm run build
```

To preview the build:

```bash
npm run preview
```

## 🐳 Docker Deployment

1. Build the Docker image:

```bash
docker build -t portfolio .
```

2. Run the container:

```bash
docker run -p 8080:80 portfolio
```

The site will be available at `http://localhost:8080`

## 🏗️ Project Structure

```
/
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable UI components
│   ├── layouts/     # Page layouts
│   ├── pages/       # Route pages
│   └── styles/      # Global styles
├── astro.config.mjs # Astro configuration
└── tailwind.config.mjs # Tailwind configuration
```

## 🔑 Features

- **Responsive Design**: Mobile-first approach with a clean, modern interface
- **Dark Mode**: System-based dark mode support
- **SEO Optimized**:
  - Meta tags
  - Open Graph data
  - Structured data (JSON-LD)
  - Sitemap generation
- **Performance**:
  - Optimized asset loading
  - Minimal JavaScript
  - Efficient image handling
- **Accessibility**: WCAG compliance with proper ARIA attributes

## 📝 Content Management

Content is managed through:

- MDX files for structured content
- Component-based architecture for easy updates
- Centralized data management for projects and experience

## 🚀 Deployment

The site is automatically deployed using GitHub Actions when changes are pushed to the main branch. The deployment process:

1. Builds the Astro site
2. Creates a Docker container
3. Deploys to Kubernetes cluster
4. Updates DNS and applies SSL certificates

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contact

For any inquiries or suggestions, feel free to:

- Email: mark.yehia@gmail.com
- GitHub: [@markmorcos](https://github.com/markmorcos)
- LinkedIn: [markmorcos](https://linkedin.com/in/markmorcos)
