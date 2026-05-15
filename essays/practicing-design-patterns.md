---
layout: essay
type: essay
title: "Practicing Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2026-04-29
published: True
labels:
  - Software Engineering
  - Design Patterns
  - Web Development
---

<style>
.essay-hero {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin: 1.5rem 0 2rem 0;
  padding: 1.25rem;
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  border-radius: 12px;
}

.essay-hero img {
  width: 230px;
  max-width: 100%;
  border-radius: 10px;
}

.essay-hero p {
  margin: 0;
}

.essay-section {
  margin: 1.5rem 0;
  padding: 1.15rem 1.25rem;
  background: #ffffff;
  border: 1px solid #dee2e6;
  border-left: 5px solid #198754;
  border-radius: 10px;
}

.essay-section h2 {
  margin-top: 0;
  margin-bottom: 0.75rem;
  font-size: 1.45rem;
}

.essay-section p {
  margin-bottom: 0;
}

.essay-section.importance {
  border-left-color: #0d6efd;
}

.essay-section.project {
  border-left-color: #6f42c1;
}

.essay-section.takeaway {
  border-left-color: #fd7e14;
}

.ai-note {
  margin-top: 2rem;
  padding: 0.9rem 1rem;
  font-size: 0.95rem;
  color: #555;
  background: #f8f9fa;
  border-left: 4px solid #6c757d;
  border-radius: 8px;
}

@media screen and (max-width: 700px) {
  .essay-hero {
    flex-direction: column;
    align-items: flex-start;
  }

  .essay-hero img {
    width: 100%;
  }
}
</style>

<div class="essay-hero">
  <img src="../img/design-patterns-logo.png" alt="Design patterns illustration">

  <p>
    When building software, it quickly becomes clear that many problems are not entirely new. The same types of challenges show up again and again, just in slightly different forms. Design patterns provide general solutions for these recurring problems and help developers organize code in a cleaner, more reliable way.
  </p>
</div>

<div class="essay-section">
  <h2>Recognizing Patterns in Code</h2>

  <p>
    Design patterns are not specific pieces of code. They are structured approaches that guide how systems should be organized. Instead of reinventing a solution every time a familiar problem appears, developers can use patterns as a reliable starting point. This makes code easier to understand, easier to change, and easier to maintain over time.
  </p>
</div>

<div class="essay-section importance">
  <h2>Why They Matter</h2>

  <p>
    One of the biggest advantages of design patterns is that they create a shared language among developers. Saying that part of a project follows a certain pattern can quickly communicate how it is structured and how different parts interact. Patterns also help avoid messy code by encouraging separation of concerns and modular design. This becomes especially important as projects grow larger and more people begin working on the same codebase.
  </p>
</div>

<div class="essay-section project">
  <h2>Patterns in My Project</h2>

  <p>
    In my final project, a web app that tracks real-time campus busyness, several design pattern ideas appeared naturally. The separation between database logic and the user interface reflected ideas similar to the Model-View-Controller approach because data handling and presentation were kept separate. There was also a service-like structure where centralized functions handled fetching and processing data instead of spreading that logic across many components. In addition, the interface updated when new data was submitted, which connects to the idea of the observer pattern because parts of the system reacted to changes in state.
  </p>
</div>

<div class="essay-section takeaway">
  <h2>What I Took Away</h2>

  <p>
    This helped me understand that design patterns are not just abstract concepts from a textbook. They show up naturally when building real software, especially when trying to keep a project organized. Even if I do not always know the exact name of a pattern while coding, recognizing the idea behind it helps me make better design decisions. It also helps me think about how my code will be read, changed, and extended by others in the future.
  </p>
</div>

<div class="ai-note">
  <strong>AI use note:</strong> AI was used while writing this essay. ChatGPT was asked to help condense and refine explanations while keeping the ideas clear and straightforward.
</div>
