# Déborah Pirata

**A multilingual portfolio for an artist working across illustration, performance and facilitation.**

[Visit the portfolio](https://deborah-pirata.vercel.app) · [All projects](https://github.com/alisson539/ai-product-portfolio)

| Role | Delivery | Focus |
| --- | --- | --- |
| Portfolio website developer | Client portfolio | Visual identity, multilingual presentation and responsive interaction |

## Context

This project has a deliberately straightforward purpose: present Déborah's work, communicate her different practices and make it easy to get in touch. It is a portfolio website, not a SaaS platform or an AI product.

My work was the implementation of that experience across languages and screen sizes, including the animated interactions that give the site its character.

## What I delivered

- **English, Portuguese and French:** localized content and navigation for different audiences.
- **A responsive portfolio:** presentation of artistic work and practice, with clear paths through the page and to contact.
- **Motion and interaction:** scroll-driven transitions and reveals supporting the visual direction.
- **Accessible motion behavior:** reduced-motion handling and readable content without depending on animation.
- **Navigation continuity:** handling language changes and section links as part of the same browsing experience.

## Implementation decisions

### Keep the product appropriately simple

The delivery focuses on presentation and contact rather than adding accounts, payments or a custom back office that the project does not need. Its value is a coherent public experience, not a long feature list.

### Motion has to survive real navigation

An animated page is not only opened at the top. Visitors change language, follow a section link or return to a scrolled position. The implementation coordinates the motion lifecycle with those entry paths so the visual experience is not tied to one clean initial load.

### Separate content from motion behavior

Language content and the animation lifecycle are managed separately. The portfolio can present the same work in three languages while retaining consistent interactions and respecting a visitor's reduced-motion preference.

## Delivery and access

The [portfolio](https://deborah-pirata.vercel.app) is publicly accessible and can be explored without an account.

**Technology:** TypeScript, Next.js, React, GSAP and Lenis.

This repository contains the public case study. The implementation remains private; the artist's images, writing and other creative assets are not redistributed here.
