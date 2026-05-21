# Documentation Study: Application and Pitfalls of Plant ID Apps for Urban Flora and Citizen Science Studies

## Article Information

| Field | Details |
|---|---|
| Article Title | *Application and pitfalls of the use of plant ID apps for urban flora and citizen science studies* |
| Authors | Hamlyn Jones and Amanda J. Jones |
| Year | 2025 |
| Journal | *Plant Ecology & Diversity* |
| DOI | https://doi.org/10.1080/17550874.2025.2476938 |
| Project Connection | VeraProject plant care and plant identification support |

---

## Purpose of This Study Section

We are using this article to understand how plant identification apps can support users, while also recognizing the risks of depending too heavily on automated plant identification. Since VeraProject is designed to help beginner plant owners care for their plants, this study helps us think carefully about how accurate, useful, and trustworthy plant identification technology should be.

This article is especially relevant because our project involves plant information, personalized guidance, and beginner-friendly support. If we include plant identification or plant suggestions in VeraProject, we need to design the feature in a way that helps users without misleading them.

---

## Summary of the Article

Jones and Jones examine how mobile plant identification apps perform when identifying urban flora. The study looks at popular plant ID apps and evaluates how useful they are for amateur users, professional botanists, and citizen science projects.

The article explains that plant ID apps have improved over time, especially because many apps benefit from larger image databases and crowd-sourced contributions. However, the authors also emphasize that these apps are not perfect. Some apps may identify a plant incorrectly, especially when two species look similar or when the photo does not clearly show important plant features.

A major point from the article is that plant ID apps should not only give an answer, but should also communicate how confident the system is in that answer. This matters because users may assume that an app’s identification is always correct, even when the result is uncertain.

---

## Why This Article Matters to VeraProject

This article matters to our project because VeraProject is meant to support beginner plant owners. Our target users may not have enough plant knowledge to recognize when an identification result is wrong. Because of this, we need to avoid presenting plant information as if it is always guaranteed to be accurate.

For VeraProject, this means we should design plant identification or plant matching features with caution. We can use automated support to help users narrow down possible plants, but we should also include reminders that the result is a suggestion rather than a final expert diagnosis.

The study also supports our idea that plant care applications should be simple and beginner-friendly. However, it reminds us that simplicity should not mean hiding uncertainty. A clean interface still needs to explain when plant information may require user confirmation.

---

## How We Can Apply This to VeraProject

Based on this article, we can apply the following ideas to our project:

### 1. We should show confidence levels

If VeraProject includes plant identification, we should show a confidence level or message such as:

- “Likely match”
- “Possible match”
- “Low confidence”
- “Please compare with the plant description before saving”

This helps users understand that the system is assisting them, not replacing careful observation.

### 2. We should provide multiple possible matches

Instead of giving only one plant name, VeraProject can display a short list of possible matches. This would let users compare options and choose the plant that best fits what they see.

### 3. We should ask users for better information

If the identification is uncertain, we can guide users to provide better details, such as:

- A clearer photo
- A photo of the leaves
- A photo of the flowers, if available
- The plant’s size
- Indoor or outdoor growing conditions

This makes the app more educational because users learn what details matter when identifying plants.

### 4. We should avoid overpromising

We should not describe VeraProject as an app that always identifies plants perfectly. Instead, we can position it as a plant care assistant that helps users organize plant information and understand possible care needs.

### 5. We should separate identification from care advice

If a plant is identified incorrectly, the care advice may also be wrong. For example, one plant may need bright indirect light while another similar-looking plant may need different care. To reduce this risk, VeraProject should allow users to confirm or edit the plant before applying care reminders.

---

## Design Implications for Our Application

This study gives us several useful design decisions for VeraProject:

| Article Insight | VeraProject Design Response |
|---|---|
| Plant ID apps can be helpful but are not always accurate. | We should present identification results as suggestions, not guaranteed answers. |
| Accuracy has improved over time, but mistakes still happen. | We should include user confirmation before saving plant data. |
| Similar-looking plants can be confused. | We should provide comparison details and multiple possible matches. |
| Apps should communicate confidence. | We should add labels such as high, medium, or low confidence. |
| Plant ID apps can support learning. | We should explain why a plant may match certain features. |

---

## Possible Feature Inspired by the Study

### Plant Match Confirmation Feature

We can create a feature where VeraProject suggests a possible plant match, but the user must confirm it before the plant is added to their collection.

Example flow:

1. The user uploads or selects information about a plant.
2. VeraProject suggests one or more possible plant names.
3. The system displays basic comparison details.
4. The user confirms the correct plant.
5. VeraProject creates a care guide based on the confirmed plant.

This feature would make VeraProject more reliable because users are involved in the decision before care information is applied.

---

## Risks We Need to Consider

The article also helps us identify risks for our project:

- Users may trust the app too much and accept incorrect plant information.
- Incorrect identification may lead to incorrect care reminders.
- Beginner users may not know how to verify a plant match.
- The application may need a strong plant database to provide useful results.
- If we use AI or image recognition, implementation may be too complex for our project timeline.
- If we do not include confidence levels, users may misunderstand the reliability of the result.

---

## How This Supports Our Project Scope

This article supports our decision to keep VeraProject focused and beginner-friendly. For the first version, it may be better for us to focus on:

- Plant profiles
- Care guides
- Watering reminders
- User-confirmed plant selection
- Basic plant information

Advanced automated plant identification can be considered a future feature, but it should not be the main requirement unless we have enough time and technical ability to implement it carefully.

---

## Key Takeaways for VeraProject

- We should design VeraProject as a plant care support tool, not as a perfect plant expert.
- We should make plant identification transparent by showing uncertainty.
- We should allow users to confirm plant matches before generating care guides.
- We should avoid giving care advice based on uncertain plant identification.
- We should use clear language so beginner users understand the app’s recommendations.
- We should prioritize accuracy, trust, and usability over adding complex features too early.

---

## Connection to Our Vision Document

This article connects directly to our VeraProject vision because our goal is to help beginner plant owners understand and care for their plants. The study shows that plant identification apps can be useful, but they must be designed responsibly.

For our project, this means VeraProject should focus on helping users make better plant care decisions while being honest about system limitations. This supports our design principles of simplicity, clarity, personalization, and practicality.

---

## Reference

Jones, H., & Jones, A. J. (2025). *Application and pitfalls of the use of plant ID apps for urban flora and citizen science studies*. *Plant Ecology & Diversity*. Advance online publication. https://doi.org/10.1080/17550874.2025.2476938
