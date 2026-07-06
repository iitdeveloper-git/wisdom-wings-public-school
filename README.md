# 🎓 Wisdom Wings Public School Website

> **Wisdom Wings Public School, Gyanpur, Bhadohi** is a premier CBSE institution dedicated to nurturing academic excellence, holistic growth, and creative development.

This repository hosts the official, modern, premium, and fully responsive static website designed to provide parents, students, and staff with seamless access to school announcements, admissions, events, and resources.

---

## 🔗 Live Demo & Links

*   **Live Website:** [wisdom-wings-public-school.netlify.app](https://wisdom-wings-public-school.netlify.app)
*   **GitHub Repository:** [github.com/iitdeveloper-git/wisdom-wings-public-school](https://github.com/iitdeveloper-git/wisdom-wings-public-school)

---

## ✨ Features & Highlights

🎨 **Premium Color Theme:** Built using a modern and professional color scheme featuring **Deep Navy Blue**, **Medium Blue**, and **Golden Yellow** to match top-tier global educational institutions.

📱 **100% Responsive Design:** Optimized for all screen sizes, including desktop computers, tablets, and smartphones, with a clean sticky navigation bar and overlay mobile menu.

🖼️ **Dynamic Gallery:** Features high-quality realistic photographs of the school library, science lab, computer lab, dance studio, playground, and creative arts, integrated with category filters and a beautiful lightbox image previewer.

📞 **Floating Action Widgets:** Floating **Call Now** (blue) and **WhatsApp** (green) buttons on every page for immediate parental queries and direct admission help with pre-filled messaging.

🗺️ **Integrated Maps & Forms:** Interactive Google Maps embedding and working contact/admission forms that pre-fill email clients for smooth administration inquiries.

🔒 **SEO & Production Optimized:** Configured with clean title tags, custom meta descriptions, structured heading hierarchy, semantic HTML5 components, `sitemap.xml`, `robots.txt`, custom `404.html` page, and native hosting settings.

---

## 📄 Site Map & Pages

| Page | Filename | Description |
| :--- | :--- | :--- |
| **Home** | `index.html` | Hero header, school values, announcements carousel, testimonials, location map, and CTA. |
| **About Us** | `about.html` | Core vision, mission statement, messages from key administration, and historical milestones. |
| **Admissions** | `admission.html` | Admission procedure details, age criteria, fee instructions, and interactive inquiry form. |
| **Events** | `events.html` | Recent celebrations, athletic updates, calendars, and circular summaries. |
| **Gallery** | `gallery.html` | Filterable grid showcasing campus facilities, class IT infrastructure, labs, and co-curricular programs. |
| **Contact Us** | `contact.html` | Address details, direct telephone links, email buttons, Google Map integration, and query form. |
| **CBSE Disclosure** | `disclosure.html` | Mandatory public disclosure panel as requested by CBSE guidelines. |
| **Privacy Policy** | `privacy.html` | Standard privacy norms, user data safety terms, and cookies declarations. |
| **Terms of Use** | `terms.html` | Usage guidelines for the official school website and digital information. |
| **404 Page** | `404.html` | Clean, interactive page for missing links returning users back to safety. |

---

## 🛠️ Technology Stack

*   **HTML5** - Semantic layout structure.
*   **CSS3** - Custom variables design system, flexbox/grid layout, premium hover animations.
*   **JavaScript (ES6)** - Lightbox viewer, announcements slider, and mobile menu toggle.
*   **FontAwesome Icons** - Clean modern typography icons.
*   **Netlify** - High-speed global static hosting.

---

## 📂 Project Directory Structure

```text
wisdom-wings-public-school/
├── assets/
│   ├── css/
│   │   └── style.css            # Primary stylesheet (Colors, layout, animations)
│   ├── js/
│   │   └── main.js             # Form handling, gallery lightbox, slider logic
│   ├── original/               # High-res assets (video clips, school photos, logos)
│   └── gallery/                # Facility graphics and campus layouts
├── index.html                  # Homepage
├── about.html                  # About Us
├── admission.html              # Admission guidelines
├── events.html                 # Events calendar
├── gallery.html                # Gallery page
├── contact.html                # Contact Us
├── disclosure.html             # CBSE Public Disclosure
├── privacy.html                # Privacy policy
├── terms.html                  # Terms & Conditions
├── 404.html                    # Interactive error page
├── sitemap.xml                 # Search Engine sitemap
├── robots.txt                  # Search Engine crawling index
└── netlify.toml                # Netlify deployment configurations
```

---

## 🚀 Local Run & Development

Since this is a fully client-side static project, no complex node installation or backend server is needed. 

### Option 1: Direct Open
Simply double-click `index.html` on your local system to load the website inside any browser.

### Option 2: Local Static Server (Recommended)
To test absolute URLs, sitemaps, and correct form redirects, serve the project root using a simple HTTP server:
```bash
# Using Python
python -m http.server 8000

# Using Node (npm)
npx serve .
```
Then visit: `http://localhost:8000` or `http://localhost:3000` in your web browser.

---

## 🌐 Deployment

This website is configured to auto-deploy on Netlify. Any change pushed to the `main` branch of this GitHub repository will trigger a clean, lightning-fast CDN rebuild and update the live URL instantly.
