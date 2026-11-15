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

## Why a design system pays off when you have many products

- **Each decision is made once.** A date picker is designed, approved and built one time, then reused on six platforms instead of being rebuilt six times.
- **Brands stay different where it matters.** Tokens carry each brand’s colours and type, so products keep their own look on top of the same components.
- **Reviews are about the product, not the pixels.** When everyone has signed off on a component, there is no room to argue about the shade of a button again, and the conversation moves to what the feature should do.
- **People can move between teams.** A designer who knows the system can open any product file and start working the same day.

## What I did

- **Made the case.** Took the idea to the design lead, then defended it in front of the managers and the founder.
- **One system for all products.** Built tokens for colour, type, spacing and radius, with a theme for each brand, so a component changes its look by switching a theme rather than being redrawn.
- **Components with every state.** Buttons, inputs, calendars, the search bar, the traveller selector and 2,000+ components and variants in total, each with its states: default, hover, focus, filled, error and disabled.
- **Documentation in Confluence.** Wrote detailed usage rules for every component, so developers and designers had one source of truth.
- **Presented every release.** Ran component presentations for analysts, managers, developers and designers before a component went into production.
- **Files and handoff.** Rebuilt how design files are structured, stored and handed off, after years of growing chaos.
- **Kept it alive.** Designers came to me with new cases, and I extended the components as they appeared.

![Theme tokens: one palette structure with accents for each brand]({{ '/assets/img/design-system/colors.webp' | relative_url }})

![Type styles for desktop and mobile. The app uses the same names]({{ '/assets/img/design-system/typography.webp' | relative_url }})

![Buttons: four styles, five sizes, every state including loading]({{ '/assets/img/design-system/buttons.webp' | relative_url }})

![Search bar components for trains and tours, with filled and disabled states]({{ '/assets/img/design-system/search-components.webp' | relative_url }})

![How the search bar behaves: round trip, date pickers, search history and destination picker]({{ '/assets/img/design-system/search-examples.webp' | relative_url }})

![Components presentation for the team: buttons, inputs and colour styles]({{ '/assets/img/design-system/presentation.webp' | relative_url }})
