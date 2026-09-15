You are working on the buildmy.house marketing website repo.

The live site is at https://buildmy.house — a Sweet Home 3D–inspired home design app called "House Designer".

## Current site (for context only — we are rebuilding from scratch)

The existing homepage is a clean, minimalist single-page site with:
- Nav: HOME, ABOUT, PRICING, DOCS, CONTACT + "Start designing ↗" CTA
- Hero: eyebrow "A BETTER BLUEPRINT FOR LIVING", h1 "Make room for good ideas.", short paragraph, CTA "Build your first plan ↗"
- Three numbered product highlights: "01 / DRAW — Think in plans", "02 / SEE — Walk it through", "03 / SHARE — Make it legible"
- Footer: "© 2026 HOUSE DESIGNER" + "MADE FOR ROOMS WITH A POINT OF VIEW."

Brand name in navigation is "House Designer" with "HD" mark.

## Task

Build a completely new marketing website for buildmy.house / House Designer. This is a fresh start, not a tweak. Figure out the design, content, and structure yourself — make it distinctive, warm, and modern, with a clear point of view. The current site is fine as a reference but the new one should feel like a genuine step up.

## What the site is for

House Designer is a desktop home design app (Sweet Home 3D–inspired) that turns early sketches into clear, considered spaces. Its audience is people who want to explore the shape of a home before a single wall goes up — homeowners, renters planning a change, small-scale designers.

## Requirements

1. **Tech**: The site is an Astro + Cloudflare Workers site (that is the existing stack — keep using it). Output must be deployable/renewable through the existing pipeline. Use the existing repo, do not create a parallel site folder.
2. **URL**: The site lives at https://buildmy.house — do not build a separate domain or subdirectory for this.
3. **Pages/sections**: At minimum cover the same zones the current site has (home, about, pricing, docs, contact) but in a fresh way. You may add sections if they strengthen the pitch. Homepage is the priority; other pages should at least exist and feel consistent.
4. **Content**: Write real, ownable copy — not placeholder lorem ipsum. The tone should be confident and a bit editorial, not generic SaaS. Lead with the idea that House Designer is for people who think in plans.
5. **Visuals**: Make it feel warmer, richer, and more distinctive than the current site. Use a considered color palette, real typography choices, and purposeful layout — not a default template look. Include some visual interest on the homepage (hero, sections, not just text blocks).
6. **CTA**: There should be a clear primary CTA to start using / download / try House Designer. Make it present and prominent.
7. **Quality**: The result should look intentional end to end — consistent type scale, spacing, colors, component language. No dead links to nowhere, no broken layout. Check what you ship.
8. **Performance/accessibility basics**: Semantic HTML, reasonable contrast, real alt text where images are used, no egregious bloat.

## Definition of done

- A fresh homepage that feels like a real marketing site for House Designer, with distinct sections and real copy.
- Other core pages (about, pricing, docs, contact) exist and feel like part of the same site.
- The site builds and serves without console errors on a normal page load.
- You can point to the top of the homepage and describe what a visitor sees and why it works.

## Process

1. Explore the existing website repo to understand the current Astro/Cloudflare setup, deploy config, component conventions, and how the live site is built/served.
2. Plan the new site: structure, sections, copy direction, visual direction — keep it coherent.
3. Build it — homepage first, then remaining pages.
4. Verify it works (build + serve locally or via the deploy workflow, check the homepage renders correctly, no console errors).
5. Report back what you built and how to see it.

Do not ask the user for direction. Make the decisions and own them. If something genuinely can't be discovered (e.g. a deploy secret or a repo path), make a reasonable assumption and note it in your final report rather than stalling.
