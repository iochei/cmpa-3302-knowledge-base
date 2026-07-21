# Analysis of Wikipedia's Organizing System

## Introduction
For this analysis, I have chosen to examine the organizing system of Wikipedia (wikipedia.org). As one of the world's largest and most popular general reference works, Wikipedia presents a unique case: a massive, collaboratively built, and constantly evolving knowledge base. Its organizing system must facilitate both rapid information retrieval for specific queries and broad, exploratory browsing for millions of unique visitors daily.

## 01. Primary Resources
The primary resources being organized on Wikipedia are **pages (or articles)**. Each article is a digital document dedicated to a specific entity, concept, or event. Within this system, a resource includes:
*   **The Article Body:** The main encyclopedic text, providing information and citations.
*   **Structured Data (Infoboxes):** Key facts about the subject presented in a consistent, tabular format on the right side of the screen.
*   **Multimodal Media:** Images, videos, and audio files embedded within the articles.
*   **Metadata:** Elements such as the page title, revision history (the "View history" tab), discussion pages ("Talk"), and interlanguage links.

## 02. Primary Interactions
Wikipedia is designed to support several fundamental information interactions:
*   **Specific Fact Retrieval (Fact-Checking):** Users often come to Wikipedia with a specific question (e.g., "When was the Eiffel Tower built?"). They use the search bar or Ctrl+F within an article to quickly locate this single data point.
*   **Research and Learning:** Users read entire articles to gain a comprehensive understanding of a topic.
*   **Non-Linear Browsing (Serendipitous Discovery):** This is a primary interaction supported by the system's architecture. A user might start on one page, follow a hyperlink to a related concept, and continue down a "rabbit hole" of information.
*   **Knowledge Contribution:** A unique aspect of Wikipedia's system is that it allows (and encourages) users to be contributors, supporting the interaction of editing and creating new resources.

## 03. Classification System
Wikipedia primarily uses a complex **associative classification system**, augmented by a broad **hierarchical system**.

*   **Associative (Folksonomy/Categories):** The most visible classification is the **Category system**. At the bottom of almost every article is a list of categories (e.g., "Category:1991 births" or "Category:Impressionist painters"). This is a non-hierarchical, multi-parent system that allows articles to belong to many different, overlapping topics.
*   **Hierarchical:** Wikipedia maintains a broad, shallow hierarchy through its main portal and overarching subjects, but this is less critical to daily user navigation than the associative links.
*   **Effectiveness:** This hybrid system is **highly effective** for its intended audience. The general public does not need a strict, rigid Dewey Decimal-style hierarchy to find information about popular culture or history. The associative network (hyperlinks) and the flexible category tags align with how people naturally connect ideas.

## 04. Representation of Relationships
Relationships between resources are represented in multiple, highly effective ways:

*   **Hyperlinks (The "Web" of Relationships):** This is Wikipedia's most defining feature. The blue text within the article body creates direct, **associative relationships** between concepts. Clicking a link from "Barack Obama" to "Harvard Law School" instantly connects two distinct entities based on their real-world connection.
*   **Infoboxes (Structured Data Relationships):** Infoboxes use key-value pairs to define specific relationships. For example, in a "City" article, the infobox explicitly lists "Country: France," "Mayor: Anne Hidalgo," and "Sister cities: Rome."
*   **"See Also" Sections:** This is an explicitly curated list at the end of an article, providing direct links to related topics that might not be explicitly mentioned in the text but are topically relevant.
*   **Categories and "Subcategories":** As mentioned in the classification section, categories establish **broad topical relationships**. An article on "The Godfather" is in "Category:1972 films" and "Category:American Mafia films," instantly relating it to other films in those groups.
*   **Template:Main:** This template is often used at the start of a section (e.g., in a "History" section of a country article) to link directly to a more detailed, dedicated article (e.g., "Main article: History of France"), establishing a parent-child relationship between the pages.

---

#### **Step 3: Commit and Submit**

Once the text is pasted into the editor box on GitHub:

1.  **Scroll down** to the **"Commit changes"** box.
2.  **Add a description:** "Submitting Assignment 02 - Analysis of Wikipedia"
3.  **Ensure "Commit directly to the main branch" is selected.**
4.  **Click the green "Commit changes" button.**

Your file is now saved in your repository and officially submitted.

#### **Step 4: Final Verification on Canvas (Optional but Recommended)**

1.  Go to Canvas and open Assignment 02.
2.  Paste the public URL of your new file into the submission box (e.g., `https://github.com/[your-username]/[your-repo-name]/blob/main/org-system-analysis.md`).
3.  Click **"Submit."**
