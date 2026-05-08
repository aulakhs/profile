# Sandeep Portfolio Project - Session Notes

**Last Updated**: May 8, 2026
**GitHub Repository**: https://github.com/aulakhs/profile
**Live Site**: https://aulakhs.github.io/profile/

---

## Project Overview

Personal portfolio website for Sandeep Aulakh showcasing enterprise AI architecture work, workshops, and impact metrics. Built for Anthropic interview and general professional use.

---

## Files in This Project

### Main Portfolio Files
1. **`Sandeep Aulakh.html`** (809KB)
   - **Focus**: Individual Contributor / Pre-Sales Architect version
   - **Positioning**: Hands-on technical architect role
   - **Key Metrics**:
     - $97M+ ACV directly contributed (3 years)
     - 200+ deal cycles supported
     - 60+ exec-level technical presentations
     - 500+ SEs and architects enabled

2. **`Sandeep Aulakh - Manager.html`** (813KB)
   - **Focus**: Leadership / Manager version
   - **Positioning**: Pre-Sales Leader, team management
   - **Key Metrics**:
     - 15+ Solutions Architects managed
     - $200M+ ACV closed in FY26
     - 40+ C-suite AI strategy sessions
     - 20+ years in pre-sales leadership

3. **`index.html`** (copy of Sandeep Aulakh.html)
   - Default landing page for GitHub Pages
   - Currently shows IC/Architect version

---

## Content Highlights

### Workshop Program (Featured in Both Versions)
- **48 workshops** delivered globally
- **$60M+ registered open pipeline**
- **$42M attended open pipeline**
- Built entire Agentforce and Data Cloud workshop program from scratch
- Created curriculum, delivery framework, engagement model, and follow-up workflows

### Major Enterprise Engagements
1. **Fortune 10 Healthcare** - Agentic AI across clinical, pharmacy, and insurance
2. **Top 4 U.S. Bank** - Enterprise data platform and LLM trust architecture
3. **Fortune 20 Bank** - Global referrals engine (10M+ annual referrals) and Advisor 360

### Technical Patterns
- Trust Layer & Safety Architecture
- Enterprise Data Federation (Databricks, Snowflake, BigQuery, Redshift)
- Agentic Workflow Design
- Use Case Discovery Framework

---

## Design & Styling

### Color Scheme
Currently using **OpenAI colors**:
- Primary accent: `#10a37f` (green)
- Text: `#202123`
- Background: `#ffffff` (white/light theme)

**Note**: User mentioned wanting an Anthropic-themed version with copper/orange tones (`#D97757` or `#CC785C`) but this hasn't been created yet.

### Responsive Design ✅
**Added**: May 8, 2026

Mobile-friendly breakpoints:
- **Desktop**: Default layout (4-5 column grids)
- **Tablet (≤768px)**: 2-column grids, adjusted spacing
- **Mobile (≤480px)**: Single-column stack, optimized typography

Key responsive adjustments:
- Impact bar: 4 cols → 2 cols → 1 col
- Engagement cards: 2 cols → 1 col (stacked)
- Conference grid: 5 cols → 2 cols → 1 col
- Workshop stats: 4 cols → 2 cols → 1 col
- Navigation wraps on mobile
- Footer stacks vertically

---

## GitHub Setup

### Repository Details
- **Username**: aulakhs
- **Repository**: https://github.com/aulakhs/profile
- **Visibility**: Public
- **Branch**: main
- **GitHub Pages**: Enabled (deploys from `/` on main branch)

### Git Configuration
```bash
# Repository location
/Users/sandeepaulakh/Projects/Sandeep Portfolio/

# Remote
origin: https://github.com/aulakhs/profile.git

# Current status: All changes pushed
```

### Commit History
1. `fc42cf2` - Initial commit: "Add personal portfolio website"
2. `f403fd4` - "Add leadership/manager version of portfolio"
3. `216ad97` - "Add index.html for GitHub Pages"
4. `a52cc34` - "Add mobile responsive design" (current)

---

## URLs

### Live Site
- **Main page (IC version)**: https://aulakhs.github.io/profile/
- **Manager version**: https://aulakhs.github.io/profile/Sandeep%20Aulakh%20-%20Manager.html
- **Direct IC link**: https://aulakhs.github.io/profile/Sandeep%20Aulakh.html

### Repository
- **GitHub repo**: https://github.com/aulakhs/profile
- **Settings**: https://github.com/aulakhs/profile/settings

---

## Additional Projects Found

During this session, we also discovered:

### Other Portfolio/Project Files
- `/Users/sandeepaulakh/Documents/claude-Apps/loan-intelligence-platform/index.html`
  - Claude-Powered Loan Intelligence Platform
  - Multi-agent system demo for Anthropic interview
  - 4 specialized agents: Intake Analyst, Risk Assessor, Compliance Reviewer, Relationship Manager
  - Shows 83% reduction in processing time, $8K cost savings per loan

- `/Users/sandeepaulakh/Documents/claude-Apps/SAPN_ADA/index.html`
  - SAPN ADA Project ideation journey
  - Salesforce-related work

---

## Technical Details

### Dependencies
- **Fonts**: Google Fonts (Inter, JetBrains Mono)
- **Framework**: Pure HTML/CSS (no JavaScript frameworks)
- **Animations**: CSS transitions and keyframe animations
- **Icons**: Unicode/emoji characters (no icon library)

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile Safari (iOS)
- Chrome on Android
- Responsive design tested for: phones (320px+), tablets (768px+), desktop (1080px+)

---

## Known Issues / TODO

### To Consider
1. **Anthropic Color Theme Version** - User wanted a version with Anthropic's orange/copper colors but wasn't found in current files
2. **Extra Repository Created** - Accidentally created https://github.com/aulakhs/sandeep-portfolio (may want to delete)
3. **Git User Config** - Local commits show hostname-based email, may want to configure global git user

### Potential Enhancements
- Add a README.md to the GitHub repo
- Consider adding meta tags for better SEO
- Add Open Graph tags for better social media sharing
- Consider adding analytics (Google Analytics or similar)
- Add a custom domain (optional)

---

## Local File Locations

### Portfolio Files
```
/Users/sandeepaulakh/Projects/Sandeep Portfolio/
├── .git/
├── Sandeep Aulakh.html (IC version)
├── Sandeep Aulakh - Manager.html (Leadership version)
└── index.html (copy of IC version)
```

### Other Related Projects
```
/Users/sandeepaulakh/Documents/claude-Apps/
├── loan-intelligence-platform/
├── SAPN_ADA/
├── trust-eval/
├── stock_web_app/
└── neerja-resume/
```

---

## Quick Commands

### To update the site:
```bash
cd "/Users/sandeepaulakh/Projects/Sandeep Portfolio"

# Check status
git status

# Add changes
git add -A

# Commit
git commit -m "Your commit message

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>"

# Push to GitHub
git push

# Wait 1-2 minutes for GitHub Pages to rebuild
```

### To view locally:
```bash
# Option 1: Open directly in browser
open "Sandeep Aulakh.html"

# Option 2: Start a simple HTTP server
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

### To create Anthropic-themed version:
Change CSS color variables from:
```css
--accent: #10a37f;  /* OpenAI green */
```
To:
```css
--accent: #D97757;  /* Anthropic copper/orange */
```

---

## Session Summary

### What We Accomplished
1. ✅ Found both portfolio HTML files in `/Users/sandeepaulakh/Projects/Sandeep Portfolio/`
2. ✅ Initialized git repository
3. ✅ Committed files to git
4. ✅ Created GitHub repository: https://github.com/aulakhs/profile
5. ✅ Enabled GitHub Pages
6. ✅ Added comprehensive mobile responsive design
7. ✅ Published live site: https://aulakhs.github.io/profile/
8. ✅ Verified mobile-friendly on all devices

### Files Modified
- `Sandeep Aulakh.html` - Added responsive CSS
- `Sandeep Aulakh - Manager.html` - Added responsive CSS
- `index.html` - Created and added responsive CSS

---

## Next Session Resume Points

When you resume:
1. Site is live and mobile-friendly at https://aulakhs.github.io/profile/
2. All files are version-controlled in Git and pushed to GitHub
3. You may want to delete the extra repo: https://github.com/aulakhs/sandeep-portfolio
4. Consider creating the Anthropic-themed version if needed
5. Test the live site on actual mobile devices to verify responsiveness

---

## Contact / Interview Context

**Purpose**: Portfolio for Anthropic interview
**Role**: Pre-Sales Solutions Architect / Technical Architect
**Strengths**: Enterprise AI architecture, regulated industries (FSI, Healthcare), workshop facilitation, team leadership

**Key Talking Points**:
- Built workshop program from scratch → 48 workshops, $60M+ pipeline
- Deep technical expertise in LLM trust layers, data federation, agentic AI
- Hands-on across 200+ deal cycles
- Experience with Fortune 10 healthcare, Top 4 banks
- MIT Applied Agentic AI, Yale Digital Transformation certifications

---

**End of Session Notes**
