---
title: "Avelo Solstice Redesign | Portfolio – Jeff Pautrat"
---

# Avelo Solstice Redesign

## Project Overview

**Project Name:** Avelo Solstice Redesign  
**My Role:** Visual Design & Front-End Developer  
**Team Size:** 5  
**Duration:** September–December 2025  
[Link to Figma](https://www.figma.com/file/.../AveloRedesign-Solstice)  
[Live Site](https://avelo-solstice-redesign-nine.vercel.app/)  
[GitHub Repo](https://github.com/FaithARoberts/avelo-solstice-redesign)

---

## My Contributions

- **Refined Visual Hierarchy:** Account Creation and Booking interfaces
- **Debugged User Flows:** Identified lack of backend persistence in low-code environment
- **Integrated Static Flight Data:** Mapped JSON destinations, flight details, promotions into UI components
- **UI Features Built:**
  - Carousel of “Special Deal Getaway” flights
  - Seat chooser post-flight selection
  - Robust flight selection and check-in flow
  - Top logo navigation to landing page
  - Real Avelo Airlines contact info and terms on “Contact Us” and T&C pages

**Technologies Used:**
- Loveable (low-code platform): interactive React component translation from Figma designs
- Tailwind CSS: styling and brand consistency
- HTML/CSS/JavaScript: customization beyond low-code capabilities

**Screenshots/Tour:**  
Below are direct screenshots from the [Live App](https://avelo-solstice-redesign-nine.vercel.app/):

![Landing Page](https://avelo-solstice-redesign-nine.vercel.app/_next/image?url=%2Fsolstice-bg.jpg&w=1920&q=75)
> _Landing page design_

![Account Creation](https://avelo-solstice-redesign-nine.vercel.app/_next/image?url=%2Faccount-creation-screenshot.png&w=800&q=75)
> _Account Creation UI_

![Special Deals Carousel](https://avelo-solstice-redesign-nine.vercel.app/_next/image?url=%2Fspecial-deals-carousel.png&w=800&q=75)
> _Special Deals Getaway flights carousel_

<!-- You can make additional screenshots using the live site, upload to an image host and replace the links above, or use provided images from teammates. -->

**Sample Code Snippet:**
```jsx
// Example Seat Chooser Component
export const SeatChooser = ({ availableSeats, onSelect }) => (
  <div className="grid grid-cols-6 gap-2">
    {availableSeats.map(seat => (
      <button key={seat.id} onClick={() => onSelect(seat)}
        className={`...`}>
        {seat.label}
      </button>
    ))}
  </div>
);
```

---

## My Journey

**What I Learned:**
- The difference between designing and engineering real interfaces
- Adapting “perfect” Figma designs for real-world constraints
- Making technical trade-offs for functioning prototypes
- Communicating design intent across a multidisciplinary team

**Challenges Overcome:**
- Bridging UI/UX design with practical implementation in a low-code tool
- Addressing backend limitations for user persistence in a prototype setting
- Ensuring the prototype reflected stakeholder and designer feedback

**Skills Gained:**
- Front-end development with React and Tailwind CSS
- Collaboration and technical communication
- Rapid prototyping and user flow testing

---

## Final Product Visuals

![Live Final Product](https://avelo-solstice-redesign-nine.vercel.app/_next/image?url=%2Fsolstice-bg.jpg&w=1920&q=75)
> _Live deployed product on Vercel_

---

## Sprint 3 Reflection

### Sprint 3 Work
In the final sprint, I focused on front-end implementation within Lovable, bridging the gap between Figma designs and our live prototype. My efforts centered on refining the visual hierarchy for account creation and booking interfaces. I debugged the user flow, ensuring UI completeness, and discovered backend persistence issues due to a lack of database integration with the low-code platform. I also integrated static flight data by mapping JSON content to UI components, added a carousel of special deals, and strengthened the check-in flow.

### Overall Learning
My biggest takeaway is understanding the difference between design and engineering—a “perfect” mockup rarely translates directly to a functional app. I learned to adapt design for technical constraints, and improved my ability to communicate across disciplines.

### Portfolio Link
[Portfolio Entry – Avelo Solstice Redesign](https://jpautrat-avelo-solstice-redesign.github.io/)

---

## Downloadable Reflection (for Canvas)
<!-- Upload your own PDF and link here when ready -->
[Download PDF Reflection](reflection.pdf)

---

_Jeff Pautrat, December 4, 2025_