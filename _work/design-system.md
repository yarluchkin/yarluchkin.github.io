---
title: "One design system for three travel products"
name: "Travel design system"
kind: product
order: 2
state: shipped
work: "Pitch, tokens, components, documentation, rollout"
period: "2023–2026"
scale: "2,000+ components"
role: "Initiator and owner of the design system"
lede: "When I joined the Firebird Tours group, there wasn’t even a UI kit. I proposed a design system, defended it in front of the managers and the founder, and built it so three products, each with a website and an app, could run on one set of components."
cover: "/assets/img/design-system/cover.webp"
preview: "/assets/img/design-system/preview.webp"
cover_alt: "Design system components: date pickers, inputs, colour tokens and type styles"
facts:
  Company: "Firebird Tours group"
  Period: "2023–2026"
  My role: "Initiator and owner of the design system"
  Team: "~20 developers and 5 designers; 3 products, each with a website and an app"
outcomes:
  - "Preparing mockups took about half the time it used to."
  - "Approval rounds got shorter: once a component is approved, nobody reopens the colour of a button."
  - "Designers could step into each other’s projects, and new designers got up to speed from the documentation."
  - "Three websites and three apps followed the same patterns, so travellers met the same date picker and traveller selector everywhere."
outcome_note: "The time saving is our own team estimate."
---

## Context

The group runs several travel products for travellers from all over the world: train tickets on Rail Ninja, tours on Firebird Tours and trip planning on Triptile. Each product has a website and an app, and around 20 developers and 5 designers worked on them.

## Problem

There was no shared base at all. Every mockup was drawn from scratch, and development was even slower, because the same date picker was built again for every product. Designers couldn’t step into each other’s projects, since there was nothing common to learn. Designers and developers spoke different languages, and every review turned into a debate about colours and spacing.

## Why it pays off with many products

- **Reuse.** A date picker is designed, approved and built once, then used on all six platforms.
- **Separate brands.** Each brand has its own colour and type tokens, so the products look different while sharing the same components.
- **Shorter reviews.** Approved components aren’t discussed again, so reviews are about what the feature should do.
- **Moving between teams.** A designer who knows the system can open any product’s file and start working the same day.

## What I did

- **Made the case.** Took the idea to the design lead, then defended it in front of the managers and the founder.
- **One system for all products.** Built tokens for colour, type, spacing and radius, with a theme for each brand, so a component changes its look by switching a theme rather than being redrawn.
- **Components with every state.** Buttons, inputs, calendars, the search bar, the traveller selector and 2,000+ components and variants in total, each with its states: default, hover, focus, filled, error and disabled.
- **Documentation in Confluence.** Wrote detailed usage rules for every component, so developers and designers followed the same rules.
- **Presented every release.** Ran component presentations for analysts, managers, developers and designers before a component went into production.
- **Files and handoff.** Rebuilt how design files are structured, stored and handed off to developers.
- **Support.** Designers came to me with new cases, and I extended the components for them.

![Theme tokens: one palette structure with accents for each brand]({{ '/assets/img/design-system/colors.webp' | relative_url }})

![Type styles for desktop and mobile. The app uses the same names]({{ '/assets/img/design-system/typography.webp' | relative_url }})

![Buttons: four styles, five sizes, every state including loading]({{ '/assets/img/design-system/buttons.webp' | relative_url }})

![Search bar components for trains and tours, with filled and disabled states]({{ '/assets/img/design-system/search-components.webp' | relative_url }})

![How the search bar behaves: round trip, date pickers, search history and destination picker]({{ '/assets/img/design-system/search-examples.webp' | relative_url }})

![Components presentation for the team: buttons, inputs and colour styles]({{ '/assets/img/design-system/presentation.webp' | relative_url }})
