## Portfolio/Archive

This is the place where I will storage from now my creations, ideas, experiments, drawings, research, etc. Constatly building it!

## 🌐 Website Logic & Structure

### Key Technologies & Features:

* **Astro Framework:** Serves as the primary framework, enabling hybrid rendering (server-side rendering for speed, client-side hydration for interactivity) and optimizing asset delivery for a lean, efficient website.
* **Three.js (on Main Page):** The homepage (`index.astro`) leverages the Three.js library to create an immersive and subtle 3D interactive experience. This dynamic element is carefully integrated to enhance visual appeal without detracting from the overall minimalistic feel. The Three.js scene logic is encapsulated within the `src/components/ThreeDScene.astro` component for modularity.
* **Markdown for Content:** Content for various sections (e.g., `aboutme`, `archive`, `design`, `projects`, and `blog`) is primarily managed using Markdown files. This simplifies content creation and updates, maintaining consistency and separation of content from presentation. Astro's built-in support for Markdown collections streamlines content management.
* **Global CSS Styling:** A unified design language is enforced through a global stylesheet (`public/styles/global.css`). This approach ensures consistent typography, spacing, and foundational styles across all pages, reinforcing the minimalistic aesthetic and minimizing redundant CSS.
* **File-Based Routing:** Astro's intuitive file-based routing (`src/pages/`) means that adding new sections or pages is as simple as creating new `.astro` or Markdown files within the `pages` directory, automatically generating corresponding URLs.

### 🏷️ Versioning Strategy

This project adheres to a modified Semantic Versioning approach (`MAJOR.MINOR.PATCH`) for Git commits, ensuring clear and consistent tracking of progress and changes. Each segment of the version number indicates the scope of the modifications introduced:

* **`MAJOR` Version (e.g., `1.x.x` to `2.x.x`)**:
    * Increments for significant milestones, such as the completion of an entire website section, a major design overhaul, or a fundamental structural change.
    * *Example Commit:* `1.0.0 Initial project base and homepage draft`

* **`MINOR` Version (e.g., `x.1.x` to `x.2.x`)**:
    * Increments for new features, substantial additions within existing sections, or significant enhancements that introduce new functionality.
    * *Example Commit:* `1.1.0 Integrated ThreeJS interactive elements on homepage`

* **`PATCH` Version (e.g., `x.x.1` to `x.x.2`)**:
    * Increments for backward-compatible bug fixes, minor content updates (e.g., typos, small text adjustments), styling refinements, or small performance optimizations.
    * *Example Commit:* `1.1.1 Adjusted global CSS spacing on mobile`

This structured approach makes the commit history easy to navigate, providing immediate context about the nature and impact of each change.