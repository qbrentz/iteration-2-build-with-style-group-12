# Student Name: Rin Pereira

## 1. My Assigned Work
* **Assigned Task:** Buttons
* **Files/Components:** I built the **Learning Page** (`learning-page.html`).
* **Implementation:** I implemented the main responsive grid layout for the learning topics and the video/tips section, ensuring the customized button styles were applied correctly across the page.

## 2. Bootstrap Implementation
* **Components Used:** Navbar, Offcanvas Sidebar, Cards, Bootstrap Carousel, Ratio (Embed) helper, and Badges.
* **Consistency:** I followed the visual strategy from **GA8** by using Cards for topics and the Ratio helper for video placeholders to ensure responsive scaling and theme consistency.

## 3. Technical Challenges & Solutions
* **The Challenge:** Handling the primary technical risk identified in Table 5—integrating complex components like cards inside a carousel while keeping them responsive.
* **The Solution:** I nested the Bootstrap grid system (`.row`) inside each `.carousel-item`. By utilizing display utilities like `d-none d-lg-block`, I ensured that desktop users see a three-card layout while mobile users see a single-card view, maintaining a clean UI across all breakpoints.

## 4. AI / LLM Usage
* **What I asked the AI:** "How do I make a Bootstrap carousel show 3 cards on desktop but only 1 on mobile?" and "How do I implement the Ratio helper for video placeholders?".
* **How it helped & What I learned:** The AI (Gemini) explained how to nest a `.row` inside a `.carousel-item`. I learned how to use responsive display utilities to hide or show specific elements based on the screen size, which directly solved our team's main technical hurdle.

## 5. Live Site Link
* **Live URL:** [https://sonmeza.github.io/bootstrap-starter-427/learning-page.html](https://sonmeza.github.io/bootstrap-starter-427/learning-page.html)