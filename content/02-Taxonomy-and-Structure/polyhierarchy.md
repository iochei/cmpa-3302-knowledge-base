---
title: "Polyhierarchy"
date: 2026-07-23
draft: false
tags: ["polyhierarchy", "taxonomy", "classification", "cross-linking"]
category: "Taxonomy & Structure"
---

A pure hierarchy dictates that every child node (page/item) has only one parent node. While simple, this model often fails in the real world where concepts overlap. **Polyhierarchy** is the practice of allowing a single node to belong to multiple parent hierarchies.

### The Problem with Strict Hierarchy

Consider a website about automobiles. In a strict hierarchy, a "Sports Car" page might live only here:
*   `Home > Vehicles > Cars > Sports Car`

But what if a user expects to find it here?
*   `Home > Brands > Porsche > Sports Car`

If the IA strictly enforces the first path, the user looking through the "Brands" navigation will fail to find the sports car.

### Implementing Polyhierarchy

Information Architects use several techniques to implement polyhierarchy:

1.  **Primary and Secondary Parentage:** The system designates one main parent for breadcrumbs/URL structure, but the item is tagged to appear in other category listings.
2.  **Faceted Classification:** (See next page). This is the most common modern approach, where items are not given "parents" but are assigned multiple "facets" (attributes) allowing them to be retrieved via different paths.
3.  **Cross-Linking:** Manually linking from one content page to a related page in a different hierarchy.

Polyhierarchy acknowledges that information is interconnected and resists simple tree structures.

***

**Related Concepts:**
*   [Hierarchical Structures](02-Taxonomy-and-Structure/hierarchical-structures.md)
*   [Faceted Classification](02-Taxonomy-and-Structure/faceted-classification.md)
