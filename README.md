# TeamBrick Landing Page

This repository powers the static landing site for **teambrick.co**, built with Jekyll and deployed on Cloudflare Pages.

## 🚀 Live Site
Visit us at: [https://teambrick.co](https://teambrick.co)

## 📝 How to Edit Content
1. Click any `.md` file (e.g. `index.md`, `about.md`, `contact.md`) in GitHub
2. Click the **Edit** (pencil icon) button
3. Make your changes using Markdown syntax
4. Scroll down and click **Commit changes**
5. Cloudflare Pages will automatically build and deploy your changes (usually takes 1-2 minutes)

## 📁 Repository Structure
```
teambrick-landing/
├── _config.yml              # Site configuration
├── _layouts/
│   └── default.html         # Main HTML template
├── assets/
│   ├── css/
│   │   └── style.css        # Site styles
│   └── images/
│       └── logo.png         # TeamBrick logo
├── index.md                 # Homepage content
├── about.md                 # About page content
├── contact.md               # Contact page content
└── README.md                # This file
```

## 🎨 Customization

### Colors
The site uses a brick-inspired color scheme:
- Primary: `#d2691e` (SaddleBrown)
- Hover: `#a0522d` (Darker brown)
- Background: `#fafafa` (Light gray)

### Logo
The logo is located at `assets/images/logo.png` and is automatically included in the header.

### Content
- **Homepage**: Edit `index.md`
- **About Page**: Edit `about.md` 
- **Contact Page**: Edit `contact.md`

## 🔧 Local Development

If you want to test changes locally:

1. Install Jekyll: `gem install bundler jekyll`
2. Clone this repository
3. Run `bundle install`
4. Run `jekyll serve`
5. Open `http://localhost:4000`

## 🌐 Cloudflare Pages Integration

This site is optimized for Cloudflare Pages with:
- Automatic builds on every commit
- Fast global CDN delivery
- Built-in SSL/HTTPS
- Custom domain support

### Build Settings
- **Build command**: `jekyll build`
- **Build output directory**: `_site`
- **Root directory**: `/`

## 📧 Contact
For technical issues or content questions: [admin@teambrick.co](mailto:admin@teambrick.co)

---

*Building better teams, one brick at a time.*