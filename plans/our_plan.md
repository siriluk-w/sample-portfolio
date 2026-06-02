# Portfolio Website Implementation Plan

## Objective
To develop and deploy a professional, modern, dark-themed portfolio website for a Senior UI Developer, hosted on GitHub Pages.

## Design Specifications
- **Theme:** Modern Dark Theme (using a high-contrast palette, e.g., deep charcoal background with soft primary/accent colors).
- **Typography:** JetBrains Mono (monospaced, clean, developer-focused).
- **Layout:** Responsive design suitable for mobile and desktop.

## Content Structure
1.  **Hero Section:** "Siriluk W." (Senior UI Developer) with a concise, punchy intro.
2.  **Projects Section:** Three showcased projects in a responsive grid layout.
3.  **Contact Section:** Links to professional profiles (GitHub, LinkedIn) and email.

## Implementation Steps

### Phase 1: Preparation & Setup
1.  Initialize a local directory for the project.
2.  Create a new public repository on GitHub named `siriluk-portfolio`.
3.  Set up the local directory as a Git repository and link it to the remote GitHub repository.

### Phase 2: Development
1.  **Skeleton:** Create `index.html`.
2.  **Styling:** Create `style.css` (implement dark theme, import JetBrains Mono via Google Fonts).
3.  **Layout:**
    - Build the Hero section.
    - Build the 3-project grid section.
    - Build the Contact section.
4.  **Interactivity:** Create `script.js` (for minimal interactions, if needed).

### Phase 3: Deployment
1.  Commit and push all changes to the `main` branch on GitHub.
2.  Configure GitHub Pages in the repository **Settings > Pages**.
3.  Select `main` branch and `/ (root)` folder for deployment.
4.  Verify the site is live at `https://[YOUR_USERNAME].github.io/siriluk-portfolio/`.

## Verification & Testing
- **Visual Check:** Confirm dark theme rendering and font application.
- **Responsiveness:** Test on mobile, tablet, and desktop viewports.
- **Functionality:** Check that project links and contact links work.
- **Deployment:** Confirm public access via the GitHub Pages URL.

## Migration & Rollback
- Since this is a new static site, rollback simply involves reverting the last commit in Git and pushing, or fixing the CSS/HTML and pushing again.
