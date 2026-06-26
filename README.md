# Youtube-Clone
A pixel-perfect clone of the YouTube homepage interface built from scratch using semantic HTML5 and CSS3. Features a responsive video grid layout (CSS Grid), a sleek sidebar, a sticky navigation bar, and custom hover states. Designed to master modern frontend layout techniques and responsive design principles without frameworks.
# 🎥 YouTube Homepage Clone (Front-End)

A responsive, static front-end clone of the YouTube homepage. This project focuses on utilizing clean HTML5 semantics alongside modern CSS layout architectures like **CSS Grid** and **CSS Flexbox** to mimic the look, feel, and structural scaling of the real YouTube application.

---

## 🚀 Features

- **Semantic Multi-File Style Architecture:** Fragmented style organization (`general.css`, `header.css`, `sidebar.css`) designed for seamless code maintainability.
- **Header Section (Flexbox):** Split cleanly into left, middle, and right blocks. Houses the hamburger menu, functional branding, global search input, voice activation triggers, and an absolute-positioned active notification badge (`3`).
- **Sidebar Navigation:** A compact left-anchored system complete with scalable icons mapping foundational routes like Home, Explore, and Subscriptions.
- **Main Video Matrix (CSS Grid):** A beautiful responsive layout that elegantly hosts 12 unique video card cards.
- **Video Card UI Polish:**
  - Standardized video aspect ratios with crisp absolute-positioned runtime badges (`video-time`).
  - Dual-column informational grids aligning profile pictures directly against multi-line title and channel text nodes.
  - Active anchor integration (`<a>` with `target="_blank"`) that points directly to live YouTube content assets.
- **Interactive Infrastructure:** Pre-configured structural `tooltips` markup hooks, ready for custom hover effect integrations.

---

## 📁 Project Structure

```text
├── index.html                  # Main structural HTML document (12 Video Matrix)
├── styles/
│   ├── general.css            # Base resets, layout wrappers, and global typography
│   ├── header.css             # Flexbox navigation setups, input forms, and utility buttons
│   ├── sidebar.css            # Navigation side-panel states and vertical distributions
│   └── x.css                  # Component-specific or variable style overwrites
├── icons/                     # SVG visual design assets (hamburger, logos, uploads, etc.)
├── thumbnails/                # Compression-optimized webp image backdrops (thumbnail-1 to 12)
└── channel-pictures/          # JPG/JPEG user avatar indicators (channel-1 to 12)