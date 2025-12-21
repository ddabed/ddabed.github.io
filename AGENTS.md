# Diego Dabed - Academic Personal Website

This repository contains the source code for Diego Dabed's academic personal website, hosted on GitHub Pages at `ddabed.github.io`.

## Project Overview

A professional, job-market-focused academic website for Diego Dabed, PhD candidate in Economics at Utrecht University (expected Summer 2025).

**Primary Audience:** Employers (academic job market)  
**Secondary Audience:** Academic peers, potential collaborators

## Structure

```
/
├── index.html              # Main website (single-page layout)
├── files/
│   ├── No background.png   # Profile photo
│   ├── jmp_amenities_dd.pdf        # Job Market Paper
│   └── academic_cv_diego_dabed.pdf # CV
├── .agents/
│   └── tasks/              # Implementation plans and task tracking
├── AGENTS.md               # This file
└── README.md
```

## Website Sections

1. **Sidebar** - Photo, name, title, institution, email, navigation
2. **About** - Research interests and bio (placeholder - to be refined)
3. **Job Market Paper** - Prominently featured with full abstract and download
4. **Research** - Other papers with abstracts and co-author links
5. **Teaching** - Condensed narrative of teaching experience
6. **CV** - Education summary and download link

## Design Specifications

- Single-page layout with sticky sidebar (desktop) / stacked (mobile)
- Responsive breakpoints at 800px and 500px
- Color palette: neutral blues/grays (to be refined)
- Typography: Georgia/serif for academic feel

## Co-author Links

| Name | URL |
|------|-----|
| Sabrina Genz | https://sites.google.com/view/sabrinagenz |
| Emilie Rademakers | https://sites.google.com/view/emilie-rademakers |
| Anna Salomons | https://www.uu.nl/staff/AMSalomons |
| Matias Cortes | https://sites.google.com/site/gmatiascortes/home |
| Ana Oliveira | https://sites.google.com/view/anamfoliveira |

## Next Steps

See `.agents/tasks/20251221_next_steps.md` for detailed tracking. Summary:

1. Refine personal bio/narrative
2. Add contact/social links (Google Scholar, LinkedIn, GitHub, ORCID, institutional page)
3. Consider adding awards/grants section
4. Refine color palette
5. SEO optimization, favicon, testing

---

## Agent Guidelines

### Plan & Review
Agents should follow a structured approach to task management and development:

1. **Plan**: BEFORE WRITING ANY CODE write a plan to .agents/tasks/<YYYYMMDD>_<task_name>.md
    - Describe the task, its purpose, and how it fits into the project.
    - The document should be a detailed implementation plan and the reasoning behind it, as well as tasks broken down into smaller steps.
    - Do not over plan, always think MVP.
    - Once the plan is written, first ask me to review it. Do not continue until I approve the plan.

2. **Review**: While working on the task update the plan as you work.
    - After you completed the tasks in the plan, you should update and append detailed descriptions of the changes you made, so following tasks can be easily handed off to other engineers.

3. **Finalize**: Once the tasks are complete, review the entire implementation for any inconsistencies or areas of improvement. Document any lessons learned or potential future enhancements. Update AGENTS.md accordingly.

### Technical Notes

- This is a static HTML/CSS site - no build process required
- Hosted on GitHub Pages
- Keep it simple: single HTML file with embedded CSS
- No JavaScript required for current functionality
- Test responsiveness before deploying changes

Never open the .env file or suggest changes to it unless explicitly instructed to do so.