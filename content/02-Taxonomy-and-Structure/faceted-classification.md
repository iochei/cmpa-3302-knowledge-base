---
title: "Faceted Classification"
date: 2026-07-23
draft: false
tags: ["faceted", "classification", "retrieval", "metadata"]
category: "Taxonomy & Structure"
---

Faceted classification is one of the most powerful tools in modern Information Architecture. Instead of organizing content into a single, rigid hierarchy (like the Dewey Decimal System), faceted classification describes content using multiple independent attributes, or **facets**.

### How Facets Work

Think of a book on a library shelf. It can only be in one place.

Now think of an e-commerce product page for a pair of shoes. It has many attributes:
*   **Facet 1 (Type):** Sneaker
*   **Facet 2 (Brand):** Nike
*   **Facet 3 (Color):** Blue
*   **Facet 4 (Size):** 10
*   **Facet 5 (Gender):** Men's

### Benefits for the User

A faceted system allows users to **drill down** through these attributes in any order they choose. A user might filter by "Men's" > "Blue" > "Nike", while another filters by "Nike" > "Size 10".

This solves the [Polyhierarchy](02-Taxonomy-and-Structure/polyhierarchy.md) problem elegantly. An item doesn't need to live in multiple folders; it just needs to be tagged with multiple facets.

### The IA Role

The architect's job in faceted classification is critical:
1.  **Selecting the Facets:** Choosing the attributes that are most important to the user's search tasks.
2.  **Defining Controlled Vocabularies:** Ensuring that for "Color", you use consistent terms (e.g., always "Blue", never "Azure" or "Navy") to make the facets reliable.

***

**Related Concepts:**
*   [Organization Systems](02-Taxonomy-and-Structure/organization-systems.md)
*   [Search System Interfaces](03-Choreography-and-Interaction/search-interfaces.md)
