---
layout: post
title: "Final Reflection: Evaluation, Iteration, and Lessons Learned"
date: 2026-05-20
---

# Final Reflection: Evaluation, Iteration, and Lessons Learned

## Introduction

Throughout this project, our team developed **Recovery Hub**, a web application designed to support people recovering from injuries through structured recovery guidance, progress tracking, and community support.

Unlike traditional fitness applications that focus on performance and achievement, Recovery Hub was designed to help users navigate uncertainty during recovery by providing relevant information, recovery logs, and experiences from people in similar situations.

Throughout the project, my primary responsibilities were **UI / Visual Design** and **Evaluation & Ethics**. I contributed to the development of the visual identity, including the final pixel-inspired design system, typography, iconography, layout consistency, and interface refinement. I also helped organise and analyse user testing sessions and evaluate usability, accessibility, and ethical considerations.

This final reflection evaluates the application's performance, user experience, functional requirements, and the lessons learned throughout the development process.

![Final Recovery Hub Interface]({{ site.baseurl }}/assets/pixel-style.png)

*Figure 1. Final pixel-inspired interface used in the high-fidelity prototype.*

---

## Performance Evaluation

From a technical perspective, the prototype performed reliably during user testing. Navigation between pages was responsive, content loaded quickly, and users were generally able to complete core tasks without encountering technical issues.

One advantage of the final design was its relatively lightweight structure. Recovery Hub focuses on a small number of core tasks, including viewing recovery guidance, logging recovery progress, and browsing shared experiences. This helped maintain a straightforward and efficient user experience.

However, user testing also revealed that performance extends beyond technical responsiveness. Although the system functioned correctly, some users still struggled to understand where they were within the application. This demonstrated that a technically functional system can still create usability problems if navigation and information architecture are not sufficiently clear.

If additional development time were available, I would further evaluate performance across different screen sizes and devices to ensure consistency and responsiveness in a wider range of contexts.

---

## User Experience Evaluation

The most valuable insights emerged from our final round of user testing.

### Issue 1: Users Became Lost During Navigation

Several participants reported that after moving through multiple pages, they became unsure about where they were within the application.

Although the navigation bar remained visible, users lacked clear contextual cues about their current location within the overall recovery journey. This reduced confidence and occasionally caused users to backtrack unnecessarily.

To address this issue, we introduced a subtitle navigation system across all pages. The subtitle clearly indicates the current page and section, allowing users to maintain awareness of their location within the application.

This change improved orientation and helped users navigate more confidently.

*Figure 2. Subtitle navigation system added after user testing.*

---

### Issue 2: User Identity Was Unclear Within Shared Recovery Stories

Another issue appeared within the community sharing section.

When users browsed recovery stories posted by others, several participants reported that they could not easily identify whose profile they were viewing. Although the content was visible, the absence of clear identity information reduced context and trust.

To solve this issue, we added user profile information including profile pictures, usernames, and brief personal details within the sharing interface.

This adjustment immediately improved clarity. Users could quickly recognise who created a post and better understand the background of the person sharing their experience.

*Figure 3. User profile information added to improve clarity and trust.*

---

### Issue 3: Numeric Input Created Unnecessary Friction

The original recovery logging system required users to manually enter numerical values when recording recovery information.

User testing revealed that participants often hesitated before entering values because they were unsure what numbers were appropriate. This slowed interactions and increased cognitive effort.

To improve usability, we replaced manual number entry with predefined selectable values. Instead of typing numbers, users could choose from clearly presented options.

This change made logging faster and more intuitive while reducing uncertainty during data entry.

*Figure 4. Numeric input redesigned using selectable values.*

---

## Visual Design Reflection

One of my primary contributions to the project was the visual design system.

Initially, our team explored several alternative visual directions before selecting the final pixel-inspired style.

![Initial Wireframe]({{ site.baseurl }}/assets/wireframe.png)

*Figure 5. Early wireframe used to establish information hierarchy and layout.*

We experimented with multiple visual approaches, including modern dark interfaces, minimalist light themes, and more decorative styles.

![Rejected Style 1]({{ site.baseurl }}/assets/style-dark.png)

*Figure 6. Dark dashboard-inspired concept.*

This version created strong visual impact but introduced excessive visual complexity and reduced readability.

![Rejected Style 2]({{ site.baseurl }}/assets/style-light.png)

*Figure 7. Minimal light interface concept.*

Although readable, this design lacked a distinctive identity and felt too generic.

![Rejected Style 3]({{ site.baseurl }}/assets/style-glass.png)

*Figure 8. Stylised visual concept.*

While visually interesting, decorative elements distracted users from important information.

Ultimately, we selected a pixel-inspired direction influenced by retro desktop interfaces, classic game design, Minecraft, and Nintendo-inspired aesthetics.

This approach created a unique identity while maintaining a structured and organised layout.

However, user testing also revealed weaknesses. Some typography choices reduced readability, and certain content areas felt visually crowded. These findings highlighted an important trade-off between stylistic expression and usability.

As a result, we began refining spacing, hierarchy, and typography to improve clarity while preserving the visual identity of the application.

---

## Accessibility and Ethical Considerations

As part of my Evaluation & Ethics role, I also considered accessibility and responsible design.

Accessibility became particularly important as we developed the pixel-inspired visual style. Decorative fonts and visual elements occasionally reduced readability, especially for smaller text sizes. User testing helped identify these issues, allowing us to make improvements to typography, spacing, and information hierarchy.

Ethically, Recovery Hub deals with personal recovery experiences and health-related information. Although the prototype does not collect sensitive medical records, users may still choose to share personal recovery details.

For this reason, we aimed to minimise unnecessary data collection and ensure that users maintain control over what information they choose to share publicly.

These considerations reinforced the importance of balancing visual creativity with accessibility, inclusivity, and user trust.

---

## Retrospective Assessment of Functional Requirements

Looking back at our original requirements, most core functions were successfully implemented.

The application allows users to:

- View personalised recovery guidance
- Track recovery progress through logs
- Browse recovery experiences from similar users
- Maintain a personal recovery profile
- Save useful content for later reference

However, testing showed that functional requirements alone do not guarantee a good user experience.

For example, the sharing platform technically worked from an early stage, but users struggled to identify who created each post. Similarly, navigation existed throughout development, but users still became confused about their location within the application.

These findings demonstrated that requirements should not only focus on functionality, but also on usability and clarity.

---

## Lessons Learned

This project significantly changed my understanding of design and development.

Initially, I viewed visual design primarily as an aesthetic activity. Through user testing, I learned that visual decisions directly influence navigation, comprehension, confidence, and usability.

I also learned the importance of iteration. Several design decisions appeared successful during internal reviews but revealed problems when tested with real users. Without evaluation, issues such as navigation confusion, unclear profile ownership, and inefficient input methods may never have been identified.

Most importantly, I learned that evaluation should not be treated as a final step. User feedback provided some of the most valuable insights throughout the project and directly influenced many of our final design improvements.

Overall, Recovery Hub evolved substantially through testing, reflection, and iteration. While there are still opportunities for further refinement, the final prototype demonstrates how user-centred design and continuous evaluation can create a more meaningful and effective digital experience.